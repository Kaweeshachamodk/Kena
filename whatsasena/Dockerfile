FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Kaweeshachamodk/Kena /root/KENA
WORKDIR /root/KENAs/
ENV TZ=Asia/Kolkata
RUN npm install supervisor --g
RUN yarn install -no -audit

CMD ["node", "bot.js"]
