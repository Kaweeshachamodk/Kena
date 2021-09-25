FROM fusuf/whatsasena:latest

RUN git clone https://github.com/SubadraBro/KENA /root/KENA
WORKDIR /root/KENA/
ENV TZ=Asia/Kolkata
RUN npm install supervisor --g
RUN yarn install -no-audit

CMD ["node", "bot.js"]
