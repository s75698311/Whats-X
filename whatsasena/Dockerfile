FROM fusuf/whatsasena:latest

RUN git clone https://github.com/xmtscf/Whats-X /root/Whats-X
WORKDIR /root/Whats-X/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
