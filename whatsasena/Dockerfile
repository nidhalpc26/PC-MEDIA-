FROM fusuf/whatsasena:latest

RUN git clone https://github.com/nidhalpc26/PC MEDIA /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
