This is a simple gRPC server using @grpc/grpc-js.

The server is generated by @protobuf-ts/plugin with the plugin 
parameter `--ts_opt server_grpc1`.

The service is then served by a gRPC server setup with 
@grpc/grpc-js.

The client which can be used with this server has been placed in grpc2 api. 

To run the server, execute `make`.