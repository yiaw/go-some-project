# Project 목표 
1.  `go clean architecture`를 참고하여 `Domain`, `Usecase`, `Repository`를 구분하여 개발 한다. 
2.  `Server` - `Client` 통신 메시지 정의는 `protobuf`로 정의 한다.
3.  `grpc`를 통해 서비스를 구현한다. 
4.  `grpc-ecosystem/gateway`을 통해 REST API 지원 한다.
5.  `grpc-ecosystem/middleware`를 통해 `Server` - `Client` 인증은 `jwt-token`으로 한다.
6.  `gorm`을 통해 `Database`에 접근한다.`
7.  `wire`를 통해 `Dependency Injection??` Code를 자동으로 생성 한다.
8.  `cobra를 통해 `Command Line Intetrace`를 제공 한다.
9.  `viper`를 통해 설정 파일 내용을 관리 한다.
10. `mock`을 통해 `Unit test`를 확인 한다.
11. `go test` 를 통해서 `test`와 `banch mark test`를 수행 한다.

* * *

# Project 구조 
| Path | Description |
|:---|:---|
|/go-some-project|
|/go-some-project/cmd|
|/go-some-project/cmd/app|
|/go-some-project/internal|
|/go-some-project/internal/domain|
|/go-some-project/internal/service|
|/go-some-project/internal/repo|
|/go-some-project/conf|
|/go-some-project/api|
|/go-some-project/protos|
|/go-some-project/build|

* * *

# 참고 Github Page
1. [gorm](https://github.com/go-gorm/gorm)
2. [grpc-go](https://github.com/grpc/grpc-go)
3. [grpc ecosystem/grpc-gateway](https://github.com/grpc-ecosystem/grpc-gateway)
4. [grpc ecosystem/grpc-middleware](https://github.com/grpc-ecosystem/go-grpc-middleware)
5. [jwt-go](https://github.com/dgrijalva/jwt-go)
6. [wire](https://github.com/google/wire)
7. [mock](https://github.com/golang/mock)
8. [cobra](https://github.com/spf13/cobra)
9. [viper](https://github.com/spf13/viper)

* * *
