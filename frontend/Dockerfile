FROM node:10-alpine
RUN apk add --no-cache bash

WORKDIR /app

# install and copy project
COPY ./src/package.json ./
RUN npm install
COPY ./src .

RUN npm install connect serve-static

# serve the app
CMD ["yarn" ,"run", "start"]