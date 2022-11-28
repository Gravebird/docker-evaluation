FROM nginx

WORKDIR /tmp

COPY ./index.html /www/data/index.html
COPY ./static /www/data/static
COPY ./default.conf.template /etc/nginx/templates/default.conf.template

RUN service nginx restart