FROM node:23.11.1-alpine3.21

WORKDIR /src

COPY package*.json .

RUN npm install

COPY . .

CMD [ "node",  "server.js" ]