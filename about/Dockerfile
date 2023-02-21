FROM node:lts-alpine3.17

COPY . /app

WORKDIR /app

RUN npm install

EXPOSE 4300

CMD [ "npm", "start" ]