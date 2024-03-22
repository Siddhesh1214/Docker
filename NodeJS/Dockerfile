FROM ubuntu:latest
LABEL app="nodejs"
LABEL Author="Mayur"

RUN  apt update 
RUN  apt install nodejs npm -y

COPY . .

WORKDIR nodejs-chat-app

RUN npm install

EXPOSE 3000

CMD [ "npm", "start" ]
