FROM candrania/wanew:latest

RUN git clone https://candrania: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@github.com/candrania/wanew /root/wanew
WORKDIR /root/wanew/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "assets/module.js"]
