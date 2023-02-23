FROM node:18.14.2-alpine

COPY . /app

WORKDIR /app

RUN npm install

EXPOSE 4200

CMD [ "npm", "start" ]