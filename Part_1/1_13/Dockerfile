FROM golang:1.16
EXPOSE 8080
WORKDIR /usr/src/app
COPY . .
RUN go build
RUN go test ./...
ENV PORT=8080
ENV REQUEST_ORIGIN=https://127.0.0.1:8080
CMD ["./server"]