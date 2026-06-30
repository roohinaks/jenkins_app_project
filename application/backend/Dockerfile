FROM python:alpine

WORKDIR /app

ADD . .

RUN pip install -r requirements.txt

ENTRYPOINT [ "python" ]

CMD [ "app.py" ]