FROM fusuf/whatsasena:latest

RUN git clone https://cyberchekuthan:amalvava0480@github.com/cyberchekuthan/private /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
