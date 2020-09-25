# REST_API

## ディレクトリ構造

├── docker  
│   ├── api 
│   │   └── Dockerfile  
│   └── mysql 
│       ├── Dockerfile  
│       ├── db
│       │   ├── init.sql
│       │   └── mysql_data
│       └── my.cnf
├── docker-compose.yml
├── domain
│   └── user.go
├── infrastructure
│   ├── router.go
│   └── sqlhandler.go
├── interfaces
│   ├── controllers
│   │   ├── context.go
│   │   ├── error.go
│   │   └── user_controller.go
│   └── database
│       ├── sql_handler.go
│       └── user_repository.go
|── usecase
│   ├── user_interactor.go
│   └── user_repository.go
├── server.go
├── go.mod
├── go.sum

## 環境構築

### featureブランチ
