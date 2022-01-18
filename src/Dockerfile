FROM node:16.13.2
COPY package*.json .
RUN npm install
COPY . .
EXPOSE 8080
ENTRYPOINT ["node", "server.js"]
