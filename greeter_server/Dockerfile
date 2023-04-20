FROM golang:1.20-alpine

WORKDIR /app

COPY . ./app/greeter_server

RUN ls

RUN go build -o server ./greeter_server

RUN chmod +x ./server

EXPOSE 3000

CMD ["./server"]