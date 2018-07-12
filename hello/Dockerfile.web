FROM node:9-alpine
MAINTAINER robin.github@gmail.com

RUN mkdir -p /app
COPY app.js /app/app.js
COPY package.json /app/package.json

WORKDIR /app
RUN npm install --save

CMD node app.js