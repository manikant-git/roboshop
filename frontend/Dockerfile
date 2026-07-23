FROM nginx:1.24.0-alpine3.17-slim

RUN rm -f /etc/nginx/conf.d/default.conf

COPY default.conf /etc/nginx/conf.d/default.conf
COPY static/ /usr/share/nginx/html/
