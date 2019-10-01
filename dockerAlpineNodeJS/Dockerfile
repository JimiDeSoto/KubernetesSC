FROM alpine:3.10.2

WORKDIR /app/
ADD https://raw.githubusercontent.com/cloudstateu/containers-w3-homework/master/package.json /app/
RUN npm install

ADD https://raw.githubusercontent.com/cloudstateu/containers-w3-homework/master/index.js /app/

CMD [ "node", "index.js"]
