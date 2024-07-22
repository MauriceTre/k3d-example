FROM node:21 as base

WORKDIR /home/next/app

COPY package*.json ./

RUN npm i

COPY . .

EXPOSE 3000

CMD [ "npm" , "run", "dev" ]