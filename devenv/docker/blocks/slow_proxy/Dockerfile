
FROM golang:1.23rc2 
ADD main.go /
WORKDIR /
RUN go build -o main . 
EXPOSE 3011
ENTRYPOINT ["/main"]
