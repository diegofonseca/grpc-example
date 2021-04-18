<br />
<p align="center">
  <a href="https://github.com/diegofonseca/grpc-example">
    <img src="https://grpc.io/img/logos/grpc-logo.png" alt="Logo" width="80">
  </a>

<h3 align="center">GRPC Example</h3>


### Built With

* [Go 1.16](https://github.com/golang/go)


### Installation

1. Install Go
   ```sh
   brew install go
   ```

2. Install Protobuf
   ```sh
   brew install protobuf
   ```
3. Install Proto Dependency
   ```sh
   go get google.golang.org/protobuf/cmd/protoc-gen-go-grpc
   ```
4. Regenerate proto
   ```sh
   protoc --proto_path=proto proto/*.proto --go_out=pb --go-grpc_out=./pb
   ```


### Using

1. Client
   ```sh
   go run cmd/client/client.go
   ```

2. Sever
   ```sh
   go run cmd/server/server.go
   ```

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- CONTACT -->
## Contact

Diego da Fonseca - [@diegofonseca404](https://twitter.com/diegofonseca404) - contato @ diegof . com . br