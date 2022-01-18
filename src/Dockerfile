FROM node:16.13.2
WORKDIR /app
COPY package*.json .
RUN npm install
COPY . .
EXPOSE 8080
ENTRYPOINT ["node", "server.js"]


# Para construir a imagem:
# docker image build -t pmguerre/conversao-temperatura:v1 .

# docker image ls

# Para executar o container
# docker container run -d -p 8080:8080 pmguerre/conversao-temperatura:v1

# docker container ls

# Para enviar para o DockerHub
# docker push pmguerre/conversao-temperatura:v1

