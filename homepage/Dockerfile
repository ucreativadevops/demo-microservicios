FROM node:lts-alpine3.17

COPY . /app

WORKDIR /app

RUN npm install

EXPOSE 4200

CMD [ "npm", "start" ]