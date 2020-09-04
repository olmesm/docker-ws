FROM node:alpine
WORKDIR /usr/app

EXPOSE 5000

COPY ./package.json .
RUN npm install

COPY src ./src

CMD npm start
