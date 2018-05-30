FROM golang:1.9.1

RUN mkdir /app
WORKDIR /app

ADD consignment.json /app/consignment.json
ADD cli /app/cli

CMD ["./cli"]