FROM alpine:3.10.2

#Update
RUN apk add --update nodejs

#App dep
WORKDIR /app/
ADD https://raw.githubusercontent.com/cloudstateu/containers-w3-homework/master/package.json /app/
RUN npm install

#App
ADD https://raw.githubusercontent.com/cloudstateu/containers-w3-homework/master/index.js /app/


CMD [ "node", "index.js"]
