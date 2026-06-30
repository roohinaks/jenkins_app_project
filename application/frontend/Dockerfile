FROM node:slim

ENV BACKEND_URL=http://0.0.0.0:8000

WORKDIR /app

ADD . .

RUN npm install

ENTRYPOINT [ "npm" ]

CMD [ "start" ]


