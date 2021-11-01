FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/TheBlackLion17/Karnan /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/TheBlackLion17/Karnannew
RUN cp -R /root/Utils/* /root/WhatsAsenaDuplicated 
CMD ["node", "bot.js"]
