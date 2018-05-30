
build:
	protoc -I proto/consignment/ proto/consignment/consignment.proto --go_out=plugins=grpc:proto/consignment
	go build
	docker build -t consignment-service .
	docker run -p 50051:50051 consignment-service
