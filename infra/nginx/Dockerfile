FROM nginx:1.20-alpine
COPY ./infra/nginx/default.conf /etc/nginx/conf.d/default.conf
COPY ./src /work
EXPOSE 80
EXPOSE 8080
