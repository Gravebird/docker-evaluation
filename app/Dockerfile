FROM python:3

RUN useradd -m -d /app backend
USER backend

WORKDIR /app

COPY . .

RUN pip3 install flask

USER root
RUN chmod 755 ./start.sh
USER backend

EXPOSE 5000

ENTRYPOINT ["./start.sh"]