FROM ubuntu:latest

LABEL app="Nodejs"
LABEL Dev="Siddhesh"

RUN apt-get update
RUN apt install nodejs npm -y 
RUN git clone https://github.com/owanhunte/nodejs-chat-app.git

WORKDIR nodejs-chat-app

RUN npm install

EXPOSE 3000
CMD [ "npm","start"]
