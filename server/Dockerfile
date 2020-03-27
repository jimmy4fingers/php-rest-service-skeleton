FROM nginx:1.15.7-alpine

COPY ./src/docker-compose.conf /etc/nginx/conf.d/default.conf
COPY ./src/server.crt /server.crt
COPY ./src/server.key /server.key