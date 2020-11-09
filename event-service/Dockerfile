FROM node:alpine

WORKDIR /event-service
COPY package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]