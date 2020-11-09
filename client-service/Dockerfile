FROM node:alpine

ENV CI=true

WORKDIR /client-service
COPY package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]