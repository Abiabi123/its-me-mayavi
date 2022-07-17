FROM fusuf/whatsasena:latest

RUN git clone https:/its-me-mayavi/github.com/BADBMODER/Badboy /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
