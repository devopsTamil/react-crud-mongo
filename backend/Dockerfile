FROM node:latest
WORKDIR /app
COPY . .
RUN npm install
RUN npm install -g nodemon
EXPOSE 4000
CMD nodemon server.js