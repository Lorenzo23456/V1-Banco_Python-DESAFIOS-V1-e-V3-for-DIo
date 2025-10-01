# V3-Banco_Python-for-DIO
# Sistema Bancário em Python (OOP)

Este projeto é uma simulação de um sistema bancário desenvolvida em Python, com foco total na aplicação dos princípios de Programação Orientada a Objetos (OOP). O sistema foi modelado a partir de um diagrama de classes UML e evoluiu para incluir funcionalidades de negócio realistas, como planos de assinatura e cheque especial.

## Diagrama UML

O projeto segue a arquitetura definida pelo seguinte diagrama de classes:

![Diagrama de Classes](diagrama.jpg)

## Funcionalidades Implementadas

- **Gestão de Clientes e Contas:** Criação de usuários (Pessoa Física) e contas correntes associadas.
- **Transações:** Operações de depósito e saque.
- **Sistema de Planos:**
    - **Múltiplos Planos:** Gratuito, Prata, Ouro e Black, cada um com diferentes benefícios.
    - **Benefícios por Plano:** Limite de saque, quantidade de saques diários e limite de cheque especial definidos pelo plano.
    - **Assinatura Mensal:** Cobrança automática da mensalidade para planos pagos, com débito na conta do cliente.
- **Cheque Especial:** Linha de crédito disponível para clientes de planos pagos.
- **Segurança e Regras de Negócio:**
    - Bloqueio de saques caso o saldo esteja negativo devido à cobrança de mensalidade.
    - Autenticação de usuário por CPF e senha.
- **Extrato Detalhado:** Exibição do histórico de transações, saldo em conta e limite de cheque especial.
- **Suporte a Múltiplas Contas:** Um cliente pode ter mais de uma conta e escolher em qual delas operar.

## Como Executar

1.  Certifique-se de ter o Python 3 instalado.
2.  Clone ou baixe este repositório.
3.  Navegue até a pasta do projeto pelo terminal.
4.  Execute o seguinte comando:
    ```bash
    python sistema_bancario.py
    ```
5.  Siga as instruções apresentadas no menu interativo.

## Tecnologias Utilizadas

- **Linguagem:** Python 3
- **Paradigma:** Programação Orientada a Objetos (OOP)
- **Bibliotecas Padrão:** `datetime`, `textwrap`, `abc`
