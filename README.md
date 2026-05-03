# 💰 Sistema Bancário Funcional - DIO

Este projeto é uma simulação de operações bancárias desenvolvida durante o **Bootcamp da DIO (Digital Innovation One)**. O sistema utiliza o paradigma de programação funcional em Python para gerenciar usuários, contas correntes, depósitos, saques e extratos.

## 🚀 Funcionalidades

O sistema oferece um menu interativo com as seguintes operações:

- **[d] Depositar:** Realiza depósitos com validação de valor positivo.
- **[s] Sacar:** Realiza saques com validações de:
  - Saldo em conta.
  - Limite por saque.
  - Limite diário de saques.
- **[e] Extrato:** Exibe o histórico detalhado de movimentações e o saldo atual.
- **[nu] Criar Usuário:** Cadastro de clientes (Nome, CPF, Data de Nascimento e Endereço).
- **[nc] Criar Conta:** Vincula uma nova conta corrente a um usuário cadastrado.
- **[lc] Listar Contas:** Exibe todas as contas e seus respectivos titulares.
- **[q] Sair:** Encerra a aplicação de forma segura.

## 🛠️ Tecnologias e Conceitos

- **Linguagem:** Python 3.x
- **Paradigma:** Programação Funcional (Separação de lógica em funções independentes).
- **Tratamento de Dados:** Uso de listas e dicionários para persistência em memória.
- **Validações:** Regras de negócio aplicadas via argumentos posicionais e nomeados (`/` e `*`).

## 💻 Como executar o script

Certifique-se de ter o Python instalado.

1. Clone o repositório:
   ```bash
   git clone https://github.com/KxuePereira/DIO-Projeto-Banc-rio.git
   ```
2. No terminal, execute:
   ```bash
   python BancarioOTM.py
   ```

## 🧠 Destaques da Otimização

Diferente de uma versão básica, este código (`BancarioOTM.py`) inclui:
- **Refatoração em Funções:** Cada operação tem sua própria função com parâmetros específicos.
- **Validadores Python:** Uso de parâmetros *keyword-only* e *positional-only* para maior segurança na chamada das funções.
- **Tratamento de Erros:** Implementação de `try/except` para lidar com entradas inválidas do usuário.
- **Correção de Persistência:** Ajuste no retorno do contador de saques para garantir que o limite diário funcione corretamente.

## 👨‍💻 Autor
- **Kauê Vitor Pereira Santos**
- Desenvolvido como projeto prático no Bootcamp da DIO.
