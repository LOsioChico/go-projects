FROM golang:1.21.6-alpine

WORKDIR /app

COPY go.mod ./
COPY *.go ./

RUN go build -o ./bin/docker-test

CMD ["./bin/docker-test"]
