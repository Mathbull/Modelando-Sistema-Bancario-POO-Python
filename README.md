<img id="top" src="img/capa_1.jpg">

<h1 align='Center'>🏦 Sistema Bancário </h1>
<p align="center">
  <img alt="Principal linguagem do projeto" src="https://img.shields.io/github/languages/top/Mathbull/Modelando-Sistema-Bancario-POO-Python?color=56BEB8">

  <img alt="Quantidade de linguagens utilizadas" src="https://img.shields.io/github/languages/count/Mathbull/Modelando-Sistema-Bancario-POO-Python?color=56BEB8">

  <img alt="Tamanho do repositório" src="https://img.shields.io/github/repo-size/Mathbull/Modelando-Sistema-Bancario-POO-Python?color=56BEB8">
  
<p align="center">
  <a href="#dart-sobre">Sobre</a> &#xa0; | &#xa0; 
  <a href="https://github.com/Mathbull" target="_blank">Autor</a>
</p>

<br>

## :dart: Sobre ##
Este é um sistema bancário simples desenvolvido em Python, que possibilita a criação de clientes, contas bancárias e a realização de transações, como depósitos e saques.

## ⚒️ Funcionalidades Principais 
- **Criação de Clientes:** Permite adicionar novos clientes ao sistema, representados pela classe `PessoaFisica`, com informações como nome, CPF, data de nascimento e endereço
- **Criação de Contas Bancárias:** Facilita a abertura de contas bancárias através da classe `ContaCorrente`, que podem ser associadas a um cliente.
- **Depósitos e Saques:** Os clientes podem realizar depósitos e saques em suas contas bancárias.
- **Exibição de Extrato:**  Permite visualizar o extrato de uma conta bancária, mostrando todas as transações realizadas.

## 🧱 Estrutura do Código 
O código é organizado em diversas classes e funções:
### 📋 Classes 
- **Cliente (`Cliente`):** Representa um cliente do banco, contendo informações básicas como endereço e uma lista de contas associadas.
- **Pessoa Física (`PessoaFisica`):** Subclasse de `Cliente`, representa uma pessoa física com nome, data de nascimento, CPF e endereço.
- **Conta (`Conta`):** Representa uma conta bancária genérica, com número, saldo, agência e cliente associado.
- **Conta Corrente (`ContaCorrente`):** Subclasse de `Conta`, representa uma conta corrente com limite de saque e limite de saldo negativo.
- **Histórico (`Historico`):** Mantém o registro de todas as transações realizadas em uma conta.
- **Transação (`Transacao`):** Classe abstrata que representa uma transação genérica.
- **Saque (`Saque`):** Subclasse de `Transacao`, representa uma transação de saque.
- **Depósito (`Deposito`):** Subclasse de `Transacao`, representa uma transação de depósito.

### ⚙️ Funções
- **Menu (`menu()`):** Exibe um menu de opções para o usuário interagir com o sistema.
- **Filtrar Cliente (`filtrar_cliente(cpf, clientes)`):** Filtra um cliente pelo CPF na lista de clientes.
- **Recuperar Conta Cliente (`recuperar_conta_cliente(cliente)`):** Recupera a conta de um cliente (atualmente retorna apenas a primeira conta associada ao cliente).
- **Depositar (`depositar(clientes)`):** Permite que um cliente realize um depósito em sua conta.
- **Sacar (`sacar(clientes)`):** Permite que um cliente realize um saque de sua conta.
- **Exibir Extrato (`exibir_extrato(clientes)`):** Exibe o extrato de transações de uma conta bancária.
- **Criar Cliente (`criar_cliente(clientes)`):** Permite a criação de um novo cliente.
- **Criar Conta (`criar_conta(numero_conta, clientes, contas)`):** Permite a criação de uma nova conta bancária associada a um cliente.
- **Listar Contas (`listar_contas(contas)`):** Lista todas as contas bancárias criadas no sistema.
- **Main (`main()`):** Função principal que controla o fluxo do programa.
  
## ▶️ Como Usar
Para utilizar o sistema, execute o arquivo `banco_poo.py`. Isso iniciará a interação com o sistema bancário, permitindo que você escolha diversas opções do menu para criar clientes, contas bancárias, realizar transações e visualizar extratos.

## Contribuições
Contribuições são muito bem-vindas! 
Se você encontrar algum problema, bug ou tiver alguma sugestão de melhoria, sinta-se à vontade para abrir uma issue ou enviar um pull request.

Feito com :heart: por <a href="https://github.com/Mathbull" target="_blank">Matheus Santos</a>

&#xa0;

<a href="#top">Voltar para o topo</a>
