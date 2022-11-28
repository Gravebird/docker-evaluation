FROM nginx

WORKDIR /tmp

COPY . .
COPY ./default.conf.template /etc/nginx/templates/default.conf.template

RUN service nginx restart