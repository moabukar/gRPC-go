# gRPC GO

- Learning gRPC here. Nothing interesting to see here...

## Setup stuff

- `go get -u github.com/golang/protobuf/protoc-gen-go`
- `protoc --go_out=plugins=grpc:chat chat.proto`

## Generate protos

```bash
protoc --proto_path=/Users/mohameda/Documents/Learning/gRPC-go/ \
       --go_out=chat --go_opt=paths=source_relative \
       --go-grpc_out=chat --go-grpc_opt=paths=source_relative \
       /Users/mohameda/Documents/Learning/gRPC-go/chat.proto
```
