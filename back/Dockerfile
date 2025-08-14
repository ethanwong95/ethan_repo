FROM golang:1.24.2

WORKDIR /app
COPY . .
RUN go build -o app main.go

CMD ["./app"]