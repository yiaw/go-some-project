# Project 시작 목표 
## Golang을 사용하면서 공부한 것들을 활용하기 위해 시작
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

# 개발 항목
## Server-Client의 채팅 서비스
## Server TODO list
| 항목 | 세부 항목 | 구현 여부 |
|:---:|:---|:---:|
|유저 관리|회원 가입|[x]|
|유저 관리|회원 탈퇴|[x]|
|유저 관리|로그인|[x]|
|유저 관리|로그 아웃|[x]|
|유저 관리|친구 추가|[x]|
|유저 관리|친구 삭제|[x]|
|채팅방 관리|채팅방 생성|[x]|
|채팅방 관리|채팅방 삭제|[x]|
|채팅방 관리|채팅방 조회|[x]|
|채팅방 관리|채팅방 입장|[x]|
|채팅방 관리|채팅방 나가기|[x]|
|채팅방|채팅 메시지 보내기|[x]|
|채팅방|채팅 메시지 받기|[x]|
|채팅방|채팅방 방장이 특정 유저 강퇴하기|[x]|

* * * 
# Project 구조 
| Path | Description |
|:---|:---|
|/go-some-project|프로젝트 ROOT 디렉토리|
|/go-some-project/cmd|프로젝트 main.go|
|/go-some-project/internal|기능 개발|
|/go-some-project/conf|프로젝트 설정 목록|
|/go-some-project/api|Open API|
|/go-some-project/protos|Proto Buf|
|/go-some-project/build|Dockerfile&&kubernetes yaml|

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
10. [go clean architecture](https://github.com/bxcodec/go-clean-arch)

* * *
