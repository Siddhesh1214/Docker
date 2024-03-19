FROM ubuntu:latest
LABEL app="nodejs"
LABEL Author="Mayur"

RUN  apt update 
RUN  apt install nodejs npm -y

RUN npm install

EXPOSE 3000

CMD [ "npm", "start" ]