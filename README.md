## Folder Structure
```
│   .dockerignore
│   .gitignore
│   go.mod
│   README.md
│   
├───cmd
│   │   README.md
│   │   
│   └───app-name
│           main.go
│           README.md
│
├───config
│       config.go
│       README.md
│
├───docker
│       Dockerfile
│
├───internal
│   ├───foo
│   │   │   delivery.go
│   │   │   foo_repository.go
│   │   │   README.md
│   │   │   usecase.go
│   │   │
│   │   ├───delivery
│   │   │   │   README.md
│   │   │   │
│   │   │   └───http
│   │   │           handlers.go
│   │   │           handlers_test.go
│   │   │           README.md
│   │   │           routes.go
│   │   │
│   │   ├───mock
│   │   │       foo_repository_mock.go
│   │   │       README.md
│   │   │       usecase_mock.go
│   │   │
│   │   ├───repository
│   │   │       foo_repository.go
│   │   │       README.md
│   │   │
│   │   └───usecase
    ├───logger
    │       README.md
    │
    ├───metric
    │       README.md
    │
    ├───sanitize
    │       README.md
    │
    └───utils
            README.md
```
