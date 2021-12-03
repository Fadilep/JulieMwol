FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Fadilep/JulieMwol /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install -g npm@latest
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
