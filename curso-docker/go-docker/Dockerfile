FROM golang:1.20.2-alpine3.17

WORKDIR /app

COPY . /app/

RUN go build main.go

# ENTRYPOINT [ "./main"]

CMD [ "./main" ]