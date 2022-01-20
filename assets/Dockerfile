FROM candrania/WAnew:public

RUN git clone https://github.com/candrania/WAnew /root/WAnew
WORKDIR /root/WAnew/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "assets/module.js"]
