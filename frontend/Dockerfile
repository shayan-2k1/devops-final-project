FROM node:latest

WORKDIR /frontend

COPY package*.json ./

RUN NODE_ENV=development npm i

COPY . . 

CMD ["npm","start"]