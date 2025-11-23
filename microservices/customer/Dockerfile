FROM node:24.10.0-alpine3.22

WORKDIR /src

COPY package*.json .

RUN npm install

COPY . .

CMD [ "node",  "server.js" ]