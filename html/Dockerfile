FROM nginx

WORKDIR /tmp

COPY . .
RUN mv ./default.conf.template /etc/nginx/templates/default.conf.template

RUN service nginx restart