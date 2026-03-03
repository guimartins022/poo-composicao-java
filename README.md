## Desafio de Composição - Java

Projeto simples desenvolvido para praticar composição em Programação Orientada a Objetos.

A ideia foi modelar um pequeno sistema de compras, trabalhando a relação entre Cliente, Compra, Item e Produto.

## Estrutura

- Um Cliente possui várias Compras
- Uma Compra possui vários Itens
- Um Item associa um Produto a uma quantidade

Cada classe é responsável pelo que realmente faz:

- Compra calcula o total dos seus itens  
- Cliente calcula o total geral somando suas compras  

## O que foi praticado

- Composição
- Organização de responsabilidades
- Estruturação de classes
- Cálculo distribuído entre objetos

## Execução

A classe `Sistema` contém o método `main` com um exemplo de uso, criando compras, adicionando itens e exibindo o valor total do cliente no console.

---

Projeto feito com foco em consolidar fundamentos de POO e modelagem.
