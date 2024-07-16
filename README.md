### Descrição

Este repositório contém o código-fonte de um sistema de serviços de lanchonete implementado em Java. O sistema simula os fluxos de trabalho de uma lanchonete, incluindo:

- **Preparo de alimentos**: cozinheiros preparam lanches, vitaminas e combos.
- **Gerenciamento de estoque**: almoxarifes controlam a entrada e saída de itens, entregam ingredientes e trocam o gás.
- **Atendimento ao cliente**: atendentes pegam os lanches na cozinha, recebem pagamentos, servem mesas, trocam o gás e atendem pedidos de gás.
- **Pedidos**: clientes escolhem lanches, fazem pedidos, pagam contas, consultam saldo no aplicativo e pegam pedidos no balcão.

### Funcionalidades

- Simulação de preparação de lanches, vitaminas e combos.
- Controle de estoque com entrada, saída e entrega de ingredientes.
- Atendimento ao cliente com pedidos, pagamentos e serviço de mesa.
- Comunicação entre funcionários para pedidos de gás.

### Estrutura do Projeto

O projeto é organizado em pacotes que representam as diferentes áreas de funcionalidade:

- `lanchonete`: contém as classes principais do sistema, como `Estabelecimento`, `Cozinheiro`, `Almoxarife`, `Atendente` e `Cliente`.
`util`: (opcional) pode conter classes utilitárias para funções comuns, como leitura de dados ou formatação de texto.

### Exemplo de Execução

A classe `Estabelecimento` contém o método `main` que inicia a simulação do sistema. No exemplo fornecido, o código simula as seguintes ações:

1. Um cozinheiro prepara um lanche natural de hambúrguer, uma vitamina e um combo.
2. Um almoxarife controla a entrada e saída de itens, entrega ingredientes e troca o gás.
3. Um atendente pega o lanche na cozinha, recebe o pagamento, serve a mesa e troca o gás.
4. Um cliente escolhe um lanche, faz o pedido, paga a conta, consulta o saldo no aplicativo e pega o pedido no balcão.
5. O cozinheiro pede para o atendente ou almoxarife trocar o gás (demonstrando comunicação entre funcionários).

### Observações

- Este é um exemplo simplificado e não representa um sistema completo de lanchonete.
- O código pode ser expandido para incluir mais funcionalidades, como cardápio completo, sistema de pedidos online, gerenciamento de mesas, etc.
- A documentação das classes e métodos não está completa no exemplo. É recomendável adicionar documentação detalhada para facilitar a compreensão do código.

### Para executar o sistema:

1. Clone o repositório para o seu computador.
2. Compile o código Java usando um compilador Java.
3. Execute a classe Estabelecimento usando o comando java lanchonete.Estabelecimento.

### Ferramentas Recomendadas

- IDE Java (por exemplo, Eclipse, IntelliJ IDEA)
- Compilador Java
- Git (para controle de versão)

### Contribuições

São bem-vindas contribuições para melhorar o código, adicionar novas funcionalidades ou corrigir bugs. Para contribuir, siga as instruções na documentação do projeto.
