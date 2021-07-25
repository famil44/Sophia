FROM fusuf/whatsasena:latest

RUN git clone https://github.com/famil44/olivia
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
