FROM node:alpine

WORKDIR /moderation-service
COPY package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]