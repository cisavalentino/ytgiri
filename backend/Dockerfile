FROM golang:1.18-alpine

WORKDIR /apps

COPY . .

RUN go build -o todo-api

EXPOSE 8080

CMD ./todo-api
