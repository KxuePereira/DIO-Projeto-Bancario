Banco Simulado
Este é um projeto simples de simulação de operações bancárias, implementado durante o Bootcamp da DIO. O sistema permite realizar depósitos, saques, extratos e a criação de contas e usuários. A aplicação foi feita em Python e tem o objetivo de mostrar como um banco digital básico pode ser estruturado, simulando funcionalidades comuns de uma conta bancária.

Funcionalidades
O projeto oferece um menu interativo que permite realizar as seguintes operações:

Depositar: O usuário pode realizar um depósito na conta, com a validação de que o valor seja positivo.

Sacar: O usuário pode realizar saques com validações de saldo, limite e número máximo de saques permitidos.

Extrato: Exibe um extrato com as transações realizadas e o saldo atual da conta.

Criar Usuário: Permite a criação de um novo usuário com nome, CPF, data de nascimento e endereço.

Criar Conta: Criação de uma conta bancária para um usuário existente, com um número de conta e uma agência pré-definidos.

Listar Contas: Exibe todas as contas criadas, com informações como número da conta, agência e titular.

Requisitos
Python 3.x

Como usar
Execute o código em um ambiente Python.

O menu principal será exibido com as opções disponíveis. O usuário pode digitar a letra correspondente à operação desejada.

Para cada operação, você será solicitado a fornecer informações, como valores de depósito ou saque, e dados do usuário (nome, CPF, etc).

As operações de depósito, saque e extrato são realizadas para uma conta específica de um usuário.

Exemplo de uso
Depositar: Digite d e informe o valor para realizar um depósito.

Sacar: Digite s e informe o valor do saque. O sistema valida se o saldo é suficiente, se o limite é excedido ou se o número de saques foi atingido.

Extrato: Digite e para exibir o extrato de sua conta.

Criar Usuário: Digite nu para adicionar um novo usuário ao sistema.

Criar Conta: Digite nc para criar uma nova conta bancária para um usuário.

Listar Contas: Digite lc para ver todas as contas criadas.

Sair: Digite q para sair do sistema.

Estrutura do Código
O sistema é estruturado da seguinte forma:

Funções principais: Funções como depositar, sacar, exibir_extrato, criar_usuario, criar_conta, listar_contas e o menu são responsáveis pela execução das operações.

Validações: Existem diversas validações, como verificar o saldo suficiente para saques, limite de saques por dia e validade de valores informados para as transações.

Usuários e Contas: São mantidos registros de usuários e contas em listas, permitindo a consulta e interação com os dados.

Como Funciona
O usuário pode criar contas e usuários, inserindo dados pessoais.

O sistema permite realizar transações de depósito e saque, com validação de regras de negócio (como limites de saque e saldo).

O extrato exibe as transações realizadas até o momento, juntamente com o saldo da conta.

O sistema oferece um menu interativo para facilitar a navegação.

Conclusão
Esse projeto é uma simulação simples de operações bancárias, ideal para aprender como lidar com operações financeiras, validações e manipulação de dados em Python. Ele pode ser expandido para incluir funcionalidades adicionais, como transferência entre contas, cálculo de juros, e outros tipos de contas bancárias.
