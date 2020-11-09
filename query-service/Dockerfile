FROM node:alpine

WORKDIR /query-service
COPY package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]