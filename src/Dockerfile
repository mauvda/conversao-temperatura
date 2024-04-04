FROM node:20.9.0-alpine3.18
EXPOSE 8080
WORKDIR /app
COPY package*.json .
RUN npm install
COPY . .
ENTRYPOINT ["node", "server.js"]
