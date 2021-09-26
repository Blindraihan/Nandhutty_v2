FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Ajmal-Achu/Nandhutty_v2 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN git clone https://github.com/Ajmal-Achu/media
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
