<h2>Digital Innovation: Expert class - Desenvolvimento de testes unitários para validar uma API REST de gerenciamento de estoques de cerveja.</h2>

Esta API foi desenvolvida pelo instrutor Rodrigo Peleias para o bootcamp GFT START #2 Java na plataforma Digital Innovation One e pode ser encontrada no seguinte repositório: https://github.com/rpeleias/beer_api_digital_innovation_one

A proposta da atividade é trabalhar os testes unitários, então, para complementar o projeto disponibilizado, acrescentei a funcionalidade **erase** na classe *BeerService* através da técnica Test Driven Development (TDD).

Este novo método tem dois testes na classe *BeerServiceTest*, um para verificar se o estoque realmente se torna 0 e outro para verificar se uma exceção é lançada ao informar um id inválido no caminho da requisição.

Ponto de entrada da API para a execução de testes:

```
http://localhost:8080/api/v1/beers
```

São necessários os seguintes pré-requisitos para a execução do projeto:

* Java 14 ou versões superiores.
* Maven 3.6.3 ou versões superiores.

