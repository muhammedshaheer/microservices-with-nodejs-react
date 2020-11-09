FROM node:alpine

WORKDIR /comment-service
COPY package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]