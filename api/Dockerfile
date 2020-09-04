FROM node:alpine
WORKDIR /usr/app

EXPOSE 3000

COPY ./package.json .
RUN npm install

COPY src ./src

CMD npm start
