![Full Cycle](https://portal.code.education/bundles/sonbase/img/lms/LogoFCCode.png?29)
# gRPC

Criando protofile e stubs
```sh
protoc --proto_path=proto proto/*.proto --go_out=pb --go-grpc_out=pb
```

```sh
go run  cmd/server/server.go
```

Rodar server
```sh
go run  cmd/server/server.go
```

Rodar client
```sh
go run  cmd/client/client.go
```