# Banklist

## Descrição

Este projeto consiste em um sistema de banco, implementado em JavaScript. Ele permite a criação de contas bancárias com informações como nome do proprietário, movimentos financeiros, taxa de juros, código PIN, entre outros. Os usuários podem realizar operações como depósitos, saques, transferências e solicitação de empréstimos.

## Funcionalidades Principais

- **Login de Usuário**: Os usuários podem fazer login utilizando um nome de usuário e um código PIN.
- **Visualização de Movimentos**: Os usuários podem visualizar os últimos movimentos em suas contas, incluindo depósitos, saques e datas associadas a esses movimentos.
- **Transferências**: Os usuários podem transferir fundos para outras contas bancárias.
- **Solicitação de Empréstimos**: Os usuários podem solicitar empréstimos com base em seus movimentos financeiros anteriores.
- **Fechamento de Conta**: Os usuários podem fechar suas contas bancárias.
- **Logout Automático**: O sistema possui um timer de 5 minutos que faz logout automático na conta do usuário por questões de segurança.

## Estrutura de Dados

### Contas Bancárias

Cada conta bancária é representada por um objeto JavaScript com os seguintes campos:

- Nome do proprietário
- Movimentos financeiros
- Taxa de juros
- Código PIN
- Datas associadas aos movimentos
- Moeda
- Localidade

## Bibliotecas e Tecnologias Utilizadas

- JavaScript
- HTML (para a estrutura da página)
- CSS (para estilização)

## Uso do Código

1. Faça o login com um nome de usuário e um código PIN válido.
2. Visualize os movimentos recentes da conta.
3. Realize operações como transferências e solicitações de empréstimo.
4. Opere com segurança, fechando a sessão após o uso.

## Informações de Login das Contas

- **Conta 1**:

  - Nome de Usuário: js
  - PIN: 1111

- **Conta 2**:

  - Nome de Usuário: do
  - PIN: 2222

- **Conta 3**:

  - Nome de Usuário: jd
  - PIN: 3333

- **Conta 4**:
  - Nome de Usuário: nn
  - PIN: 4444

## Código Fonte

O código fonte deste projeto está disponível no GitHub: [Link para o Repositório](https://github.com/diegoo237/Banklist)

## Notas Finais

Este projeto é apenas uma implementação básica de um sistema bancário. Adapte-o conforme necessário para atender aos requisitos específicos do seu projeto.
