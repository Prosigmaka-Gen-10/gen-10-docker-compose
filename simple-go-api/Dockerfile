FROM	golang:1.19

WORKDIR	/usr/src/simple-go-api
COPY	. .
RUN		go build -o /usr/local/bin/simple-go-api ./main.go

CMD		["simple-go-api"]
