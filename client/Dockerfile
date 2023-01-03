FROM node:lts-alpine

RUN npm i -g serve

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY ..

RUN npm run build

EXPOSE 8080

CMD ["serve", "-s", "dist"]
