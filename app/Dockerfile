FROM python:3

RUN useradd -m -d /app backend
USER backend

WORKDIR /app

COPY . .

RUN pip3 install flask

EXPOSE 5000

ENTRYPOINT ["echo", "${STUDENT_NAME}\n${STUDENT_ID}", ">", "student.txt"]

CMD python web.py