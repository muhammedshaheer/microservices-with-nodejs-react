FROM node:alpine
WORKDIR /post-service
COPY package.json ./
RUN npm install
COPY ./ ./
CMD ["npm", "start"]