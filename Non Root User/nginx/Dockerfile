FROM nginx:latest

COPY ./nginx.conf /etc/nginx/nginx.conf
COPY ./default.conf /etc/nginx/conf.d/default.conf

RUN mkdir /var/www/ && \
    mkdir /var/www/html && \
    chown -R nginx:nginx /var/www/html && \
    chown -R nginx:nginx /var/cache/nginx && \
    chown -R nginx:nginx /var/log/nginx && \
    chown -R nginx:nginx /etc/nginx/conf.d && \
    touch /var/run/nginx.pid && \
    chown -R nginx:nginx /var/run/nginx.pid
WORKDIR /etc/nginx
USER nginx