# Anotaçẽs gerais sobre Golang


## Instalação
[Golang](https://go.dev/doc/install)

### Primeiros passos
- Criar o arquivo main.go
- Criar o módulo para a aplicação: `go mod init MODULE_NAME`
- Adicionar o pacote: `package main`
- Criar a função principal: `func main()`
- Como rodar: `go run main.go`

### Variáveis
- var, const
- tipos int, int8, uint, string, float ...
- Inferência usando := ex: `name := "Paulo`
- Operações em tipos numéricos devem ser do mesmo tipo

### Ponteiros
- Usar & para apontar para o local em memória de uma variável
- Exemplo de uso, ponteiro para adicionar valor em variável usando Scan: `fmt.Scan(&myVar)`
