FROM node:alpine
RUN mkdir /app
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY ./books-service.js ./books-service.js
CMD npm run start-books
