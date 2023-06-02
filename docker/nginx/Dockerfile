FROM nginx:alpine
COPY ./sites/default.conf /etc/nginx/conf.d/default.conf
WORKDIR /var/www/html

CMD ["nginx"]

EXPOSE 80 443