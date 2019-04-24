FROM nginx:1.15

RUN rm -f /etc/nginx/conf.d/default.conf

COPY nginx.conf /etc/nginx/nginx.conf
ADD ssl /usr/local/nginx/ssl

EXPOSE 443

