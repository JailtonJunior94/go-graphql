# Curso - FullCyle [Go Expert]
## Módulo [gRPC]

[gqlgen](https://gqlgen.com/)

## Iniciando template GraphQL
```
printf '// +build tools\npackage tools\nimport (_ "github.com/99designs/gqlgen"\n _ "github.com/99designs/gqlgen/graphql/introspection")' | gofmt > tools.go

go mod tidy
```

## Gerando estrutura inicial
```
go run github.com/99designs/gqlgen init
```

## Gerando/Alterando estrutura 
```
go run github.com/99designs/gqlgen generate
```