FROM nginx

WORKDIR /tmp

COPY ./index.html /usr/share/nginx/html/index.html
COPY ./static /usr/share/nginx/html/static
COPY ./default.conf.template /etc/nginx/templates/default.conf.template

RUN service nginx restart