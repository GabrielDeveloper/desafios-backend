# Desafio para Desenvolvedor(a) em .NET C#

Ficamos felizes que você tenha chegado nesta etapa do processo seletivo para desenvolvedor(a) em .NET C#. 
Nosso desafio é a construção de uma API Rest, obrigatoriamente você deve implementar uma solução com .NET C#.
* .NET Core
* POO
* SOLID
* Clear Code

#### Crie uma API Rest que faça o gerenciamento de um pedido. Nela devem conter as operações e regras abaixo:
- **Criar pedido**: Deve ser possível criar um pedido contendo Itens, Status, Customer e Total.
    - *Pedido deve ser criado com status Pendente*
- **Adicionar Item ao pedido**: Deve ser possível adicionar um item ao pedido alterando o valor Total.
- **Pagar pedido**: Deve ser a operação que altera o status do pedido para Pago.
    - *Só poderá ser pago um pedido pedido Pendente.*
- **Cancelar pedido**: Deve ser a operação que altera o status do pedido para Cancelado.
    - *Só poderá ser cancelado um pedido pedido Pendente.*
- **Estornar pedido**: Deve ser a operação que altera o status do pedido para Estornado.
    - *Só poderá ser estornado um pedido Pago.*

#### O que você deve nos entregar:
- Código fonte no Github com documentação no readme ou wiki sobre como rodar localmente a aplicação.
- Utilize banco NoSQL (preferencialmente MongoDb)
- Utilize .NET CORE;
- Documentação de como utilizar os endpoints
- Dockerizar a aplicação será um diferencial (porém não é obrigatório)

#### O que vamos avaliar:
- Solução adotada, principalmente a mudança de status do pedido.
- Cobertura de testes e a qualidade dos testes (será um diferencial)
- Qualidade de código
- Conceitos de orientação a objetos 
- Verbos e status code dos endpoints (utilize os padrões HTTP)
- Como os erros são tratados