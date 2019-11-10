FROM node:8.11-alpine

WORKDIR /usr/hola-mundo/

COPY package.json ./

RUN npm install

COPY . .

CMD npm start

EXPOSE 3000