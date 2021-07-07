FROM fusuf/whatsasena:latest

RUN git clone https://github.com/hintaga/WhatsAsenaDuplicated /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Masalli
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
