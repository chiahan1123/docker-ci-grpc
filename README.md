# docker-ci-grpc
Docker image for Continuous Integration (CI) for gRPC services

* Source Image:
  * ```golang:1.10-alpine``` (https://hub.docker.com/_/golang/)

* Supports fix for Alpine not supporting glibc (https://github.com/os72/protoc-jar/issues/15)

* Tools:
  * [dep](https://github.com/golang/dep)
  * [grpc-gateway](https://github.com/grpc-ecosystem/grpc-gateway)
  * [protoc-gen-lint](https://github.com/ckaznocha/protoc-gen-lint)
  * [golint](https://github.com/golang/lint)

Docker Hub: [docker-ci-grpc](https://hub.docker.com/r/chiahan1123/docker-ci-grpc/)
