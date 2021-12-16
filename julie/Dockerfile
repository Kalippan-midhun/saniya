FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Kalippan-midhun/saniya /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Kalippan-midhun/html

CMD ["node", "bot.js"]
