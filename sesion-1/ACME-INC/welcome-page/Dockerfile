FROM nginx:latest

COPY acme-site.conf /etc/nginx/conf.d/default.conf

RUN mkdir html

COPY index.html html/index.html
