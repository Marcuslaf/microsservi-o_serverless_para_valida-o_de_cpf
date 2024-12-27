# Validação de CPF com Azure Functions

Este projeto implementa uma Azure Function para validar CPFs (Cadastro de Pessoas Físicas) utilizando C#.

## Estrutura do Projeto

O projeto contém os seguintes arquivos principais:

- fnvalidacpf.cs: Contém a função Azure que recebe uma requisição HTTP POST com um CPF e valida se o CPF é válido.

## Como Funciona

A função fnvalidacpf é acionada por uma requisição HTTP POST. Ela lê o corpo da requisição, extrai o CPF e valida se o CPF é válido. Se o CPF for válido, a função retorna uma mensagem de sucesso. Caso contrário, retorna uma mensagem de erro.

### Exemplo de Requisição

```json

{

    "cpf": "12345678909"

}
