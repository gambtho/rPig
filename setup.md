brew install kind
kind create cluster



## local dev
https://dev.to/b0r/build-load-balancer-in-go-1oo7

go run ./main.go -port=8081 &
go run ./main.go -port=8082 &

