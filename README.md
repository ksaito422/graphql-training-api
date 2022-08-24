# GraphQL server with Golang

## Getting Started

```go
go run server.go
```

Try accessing http://localhost:8080

## 定義からコード生成

`graphql/schema.graphqls`の定義をもとに`go run github.com/99designs/gqlgen generate`を実行すると  
`graph/generated/generated.go`や`graph/model/models_gen.go`が生成されます。

## 参考

[Golang+Next.js+GraphQL](https://zenn.dev/akino/articles/a26bcf3ad2bba8)
