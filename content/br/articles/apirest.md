+++
author = "Robson Cassiano"
title = "O que é API REST?"
date = "2019-01-30"
description = "O que é uma API REST"
tags = ["api", "rest", "json"]
+++

## O que é uma API REST?

Uma API REST (Representational State Transfer) é uma interface de programação de aplicações (API) que segue um conjunto de restrições de arquitetura. Essas restrições definem como os recursos são representados, como as solicitações são feitas e como as respostas são retornadas.

As APIs REST são comumente usadas para conectar aplicações web diferentes. Por exemplo, um aplicativo de e-commerce pode usar uma API REST para se conectar a um serviço de pagamento para processar transações.

{{< youtube F9n1N8ThpF0 >}}

### Recursos e URIs

O conceito central de uma API REST é o recurso. Um recurso é um objeto ou entidade que pode ser manipulado por meio da API. Por exemplo, um recurso pode ser um produto, um usuário ou uma transação.

Cada recurso é identificado por um URI (Uniform Resource Identifier). Um URI é um endereço que identifica um recurso na web. Por exemplo, o URI /produtos/1 pode identificar um produto específico.

### Métodos HTTP

As APIs REST usam os métodos HTTP para realizar operações em recursos. Os métodos HTTP mais comuns são:

**GET:** Obter informações sobre um recurso.
**POST:** Criar um novo recurso.
**PUT:** Atualizar um recurso existente.
**DELETE:** Excluir um recurso existente.
**HEAD:** Util para obter apenas o cabeçalho da requisição e economizar dados.


### Representação de recursos

As respostas de uma API REST são geralmente representadas em JSON ou XML. JSON é um formato de texto legível por humanos que é fácil de serializar e desserializar. XML é um formato de texto mais estruturado que é mais adequado para descrever dados complexos.

**A maioria das APIs Web hoje respondem em JSON**

JSON é o formato de representação de recursos mais comumente usado nas APIs Web. Isso ocorre porque JSON é fácil de entender e trabalhar, tanto para humanos quanto para máquinas.

JSON também é um formato leve, o que o torna ideal para aplicativos móveis e dispositivos com recursos limitados.

Exemplo de JSON que representa os dados de um cliente bancário:
```json
{
  "id": 1,
  "nome": "João da Silva",
  "cpf": "123.456.789-00",
  "data_nascimento": "1980-01-01",
  "endereco": {
    "cep": "12345-678",
    "logradouro": "Rua das Flores",
    "numero": 123,
    "complemento": "Apto 101",
    "bairro": "Centro",
    "cidade": "São Paulo",
    "estado": "SP"
  },
  "contas": [
    {
      "numero": 1234567890,
      "tipo": "corrente",
      "saldo": 1000.00
    },
    {
      "numero": 9876543210,
      "tipo": "poupança",
      "saldo": 500.00
    }
  ]
}
```

### Conclusão

As APIs REST são uma ferramenta poderosa que pode ser usada para conectar aplicações web diferentes. Elas são fáceis de usar e implementar, e são amplamente utilizadas na web.