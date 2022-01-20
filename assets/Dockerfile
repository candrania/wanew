FROM blackamda/queenamdi:public

RUN git clone https://github.com/candrania/wanew /root/wanew
WORKDIR /root/wanew/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "assets/module.js"]
