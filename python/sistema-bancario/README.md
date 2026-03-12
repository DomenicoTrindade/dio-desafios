# Sistema Bancário em Python

Projeto desenvolvido como desafio prático da DIO com foco em Programação Orientada a Objetos (POO).

## Objetivo

Simular um sistema bancário permitindo:

- cadastro de clientes
- criação de contas bancárias
- depósitos
- saques
- emissão de extrato
- listagem de contas

## Conceitos aplicados

- classes e objetos
- herança
- encapsulamento
- classes abstratas
- associação entre objetos
- histórico de transações
- organização em funções de operação

## Estrutura de classes

O projeto foi modelado com base no desafio orientado a objetos:

- `Cliente`
- `PessoaFisica`
- `Conta`
- `ContaCorrente`
- `Historico`
- `Transacao`
- `Deposito`
- `Saque`

## Melhorias implementadas

Além do foco principal do desafio, foram incluídas melhorias simples:

- correção do uso de `abstractmethod`
- validação básica de CPF
- tratamento de erro para valores digitados incorretamente
- possibilidade de escolher a conta quando o cliente possui mais de uma
- exibição da data no extrato
- uso do método `adicionar_conta()` para melhor encapsulamento

## Como executar

No terminal, dentro da pasta do projeto, execute:

```bash
python desafio_sistema_bancario.py
