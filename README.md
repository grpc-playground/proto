# proto

## gen

```shell script
go get github.com/gogo/protobuf/proto
go get github.com/gogo/protobuf/protoc-gen-gogofaster
go get github.com/gogo/protobuf/gogoproto
```

## windows
`protoc -I .\pb pb\*.proto --gogofaster_out=plugins=grpc:.\pb`
