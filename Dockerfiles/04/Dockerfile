FROM golang

WORKDIR /app
ADD . /app
ENV GO111MODULE=auto
RUN go build -o meugo
ENTRYPOINT ./meugo
