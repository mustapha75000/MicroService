FROM node:alpine
RUN mkdir /app
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY ./categories-service.js ./categories-service.js
CMD npm run start-categories
