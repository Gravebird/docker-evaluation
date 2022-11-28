FROM nginx

WORKDIR /src

COPY ./index.html /src/index.html
COPY ./static /src/static
COPY ./default.conf.template /etc/nginx/templates/default.conf.template

RUN service nginx restart