FROM golang:alpine
WORKDIR /go/src
COPY go-test/web.go .
COPY go-test/go.mod .
RUN go build -o /go/web
expose 8888
CMD ["/go/web"]


