FROM ubuntu:latest
LABEL app="nodejs"
LABEL Author="Siddhesh"

RUN  apt update 
RUN  apt install nodejs npm -y

COPY . .

RUN npm install

EXPOSE 3000

CMD [ "npm", "start" ]
