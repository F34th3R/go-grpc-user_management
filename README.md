# Stage #1 - Unary Service Method

`$ protoc --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative usermgmt/usermgmt.proto`

# For testing
## Server
`$ go run usermgmt_server/usermgmt_server.go`

## Client 
`$ go run usermgmt_client/usermgmt_client.go`

# Stage #2 - Proto Messages and Persist data
