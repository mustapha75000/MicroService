FROM node:alpine
RUN mkdir /app
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY ./authors-service.js ./authors-service.js
CMD npm run start-authors
