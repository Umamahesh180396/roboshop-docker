FROM node:14
EXPOSE 8080
RUN useradd roboshop && mkdir /app
WORKDIR /app
COPY package.json .
COPY server.js .
RUN npm install
CMD [ "node", "server.js" ]
