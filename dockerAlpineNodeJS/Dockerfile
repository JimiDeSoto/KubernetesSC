FROM alpine:3.10.2

#Update & install
RUN apk update  \
    && apk add nodejs nodejs-npm

#App dep
WORKDIR /app/
ADD https://raw.githubusercontent.com/cloudstateu/containers-w3-homework/master/package.json /app/
RUN npm install

#App
ADD https://raw.githubusercontent.com/cloudstateu/containers-w3-homework/master/index.js /app/

CMD [ "node", "index.js"]
