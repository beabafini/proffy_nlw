FROM node:latest as node

WORKDIR /app

COPY package.json /app

RUN npm install --silent

COPY . .

CMD [ "npm", "start" ]