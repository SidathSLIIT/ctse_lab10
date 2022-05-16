FROM node:16

WORKDIR /app

COPY package*.json ./

COPY . .

RUN npm i

EXPOSE 8080

CMD [ "node", "server.js" ]