## Bootcamp Engenharia de Dados com Python - DIO. NTT DATA

### Projeto desenvolvido durante o desafio: *Modelando o Sistema Bancário em POO com Python* 
---

### Linguagem Utilizada:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

### Proposta:
Neste projeto, incrementamos o **Sistema Bancário em Python** desenvolvido no desafio anterior. A nova versão implementa a modelagem do sistema bancário utilizando **Programação Orientada a Objetos (POO)**, introduzindo classes para clientes e operações bancárias, como *depósito* e *saque*. O código seguiu o modelo de classes UML.

### Instruções do desafio:  

#### Melhorias e Conceitos Implementados:
> POO (Programação Orientada a Objetos):
* A estrutura do sistema foi organizada em classes, com utilização de herança, polimorfismo, e encapsulamento, seguindo boas práticas de POO.
> Classes Abstratas:
* A criação de uma classe abstrata para as transações garante que operações como *saque* e *depósito* sigam um padrão de implementação.
> Herança:
* A classe `Cliente` foi especializada em `PessoaFisica`, e a classe `Conta` foi estendida para `ContaCorrente`, permitindo que cada uma adicione características específicas.
> Polimorfismo:
* Métodos como `sacar` foram sobrescritos em subclasses para atender a diferentes regras de negócio, como o limite de saques diários.
> Encapsulamento:
* Atributos e métodos foram encapsulados para proteger a integridade dos dados e garantir que a lógica de negócios seja respeitada.

#### Regras do Sistema:

> Criação de Contas:
   * Contas podem ser criadas apenas para clientes previamente cadastrados.
   * Cada cliente pode ter múltiplas contas associadas.
> Operações de Saque:
   * O cliente pode realizar saques dentro de um limite diário de transações.
   * O valor do saque não pode exceder o saldo disponível na conta ou o limite diário estabelecido.

> Operações de Depósito:
   * Depósitos podem ser realizados em qualquer conta ativa do cliente.
   * Apenas valores positivos são aceitos.

> Exibição de Extrato:
   * O cliente pode visualizar um extrato detalhado de todas as transações realizadas, incluindo depósitos e saques.

> Listagem de Contas:
   * O sistema permite listar todas as contas associadas aos clientes cadastrados, exibindo informações como número da conta, agência, e saldo.

---
#### Saiba mais sobre o bootcamp : [Dio.](https://web.dio.me/track/953ab0a9-6d55-4e00-ab7f-5ed855d288ca?tab=path)
