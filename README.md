<img src="img/capa_1.jpg">

<h1 align='Center'>Sistema Bancário 🏦</h1>
<p align="center">
  <img alt="Principal linguagem do projeto" src="https://img.shields.io/github/languages/top/Mathbull/Modelando-Sistema-Bancario-POO-Python?color=56BEB8">

  <img alt="Quantidade de linguagens utilizadas" src="https://img.shields.io/github/languages/count/Mathbull/Modelando-Sistema-Bancario-POO-Python?color=56BEB8">

  <img alt="Tamanho do repositório" src="https://img.shields.io/github/repo-size/Mathbull/Modelando-Sistema-Bancario-POO-Python?color=56BEB8">
  
<p align="center">
  <a href="#dart-sobre">Sobre</a> &#xa0; | &#xa0; 
  <a href="#memo-licença">Licença</a> &#xa0; | &#xa0;
  <a href="https://github.com/isabellazramos" target="_blank">Autor</a>
</p>

<br>

## :dart: Sobre ##
Este é um sistema bancário simples desenvolvido em Python, que possibilita a criação de clientes, contas bancárias e a realização de transações, como depósitos e saques.

## Funcionalidades Principais ⚒️
- **Criação de Clientes:** Permite adicionar novos clientes ao sistema, representados pela classe PessoaFisica, com informações como nome, CPF, data de nascimento e endereço
- **Criação de Contas Bancárias:**Facilita a abertura de contas bancárias através da classe ContaCorrente, que podem ser associadas a um cliente.
- **Depósitos e Saques:**Os clientes podem realizar depósitos e saques em suas contas bancárias.
- **Exibição de Extrato:**  Permite visualizar o extrato de uma conta bancária, mostrando todas as transações realizadas.

## Estrutura do Código 🧱
O código é organizado em diversas classes e funções:
### Classes 📋
- **Cliente (Cliente):** Representa um cliente do banco, contendo informações básicas como endereço e uma lista de contas associadas.
- **Pessoa Física (PessoaFisica):** Subclasse de Cliente, representa uma pessoa física com nome, data de nascimento, CPF e endereço.
- **Conta (Conta):** Representa uma conta bancária genérica, com número, saldo, agência e cliente associado.
- **Conta Corrente (ContaCorrente):** Subclasse de Conta, representa uma conta corrente com limite de saque e limite de saldo negativo.
- **Histórico (Historico):** Mantém o registro de todas as transações realizadas em uma conta.
- **Transação (Transacao):** Classe abstrata que representa uma transação genérica.
- **Saque (Saque):** Subclasse de Transacao, representa uma transação de saque.
- **Depósito (Deposito):** Subclasse de Transacao, representa uma transação de depósito.
