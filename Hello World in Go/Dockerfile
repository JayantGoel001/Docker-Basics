FROM golang:alpine

COPY . /go/src/app/
WORKDIR /go/src/app/

RUN go mod init
RUN go build -o helloworld

EXPOSE 6111

CMD ["./helloworld"]