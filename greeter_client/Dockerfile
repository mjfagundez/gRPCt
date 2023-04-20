FROM golang:1.20-alpine

WORKDIR /app/greeter_client

COPY . .

RUN go build -o client ./helloworld/greeter_client

RUN chmod +x ./client

EXPOSE 3000

CMD ["./client"]
