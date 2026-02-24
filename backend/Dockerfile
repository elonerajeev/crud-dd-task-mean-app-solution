# Dockerfile For Backend App Without Multi Build stage

FROM node:20-alpine

WORKDIR /App

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8080

CMD ["node", "server.js"]

