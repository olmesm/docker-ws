FROM node:alpine
WORKDIR /usr/app

EXPOSE 9000

COPY ./package.json .
RUN npm install

COPY src ./src

CMD npm start
