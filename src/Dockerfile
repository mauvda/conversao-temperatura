FROM node
EXPOSE 8080
WORKDIR /app
COPY package-lock.json .
COPY package.json .
RUN npm install
COPY . .
ENTRYPOINT ["node", "server.js"]
