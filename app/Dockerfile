FROM node:16-slim

WORKDIR /usr/src/app

COPY package*.json ./

RUN yarn install

COPY ./ ./

CMD ["node", "index.ts"]