FROM node:lts-alpine3.17

COPY . /app

WORKDIR /app

RUN npm install

EXPOSE 4400

CMD [ "npm", "start" ]