FROM python:3

RUN useradd -m -d /app backend
USER backend

WORKDIR /app

COPY . .

RUN pip3 install flask && chmod +x ./start.sh

EXPOSE 5000

ENTRYPOINT ["./start.sh"]