# FinAPI - Financeiro

Este é um porjeto da trilha de estudos do Ignite de Nodejs sobre Repositorios

[![NodeJs](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](#)
[![Express](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)](#)

## Explicando

Este é um projeto backend em Nodejs que faz o CRUD de gestão financeira pessoal, simulando depositos e gastos.


## Instruções

`yarn dev` - Inicia a aplicação


## Requisitos

-[x] Deve ser possível cirar uma conta

-[x] Deve ser possível buscar o extrato bancário do cliente

-[x] Deve ser possível realizar um depósito

-[x] Deve ser possível realizar saque

-[x] Deve ser possivel buscar o extrato bancário do cliente por data

-[] Deve ser possivel atualizar dados da conta do cliente

-[] Deve ser possivel obter dados da conta do cliente

-[] Deve ser possivel deletar uma conta


## Regra de Negócio

-[x] Não deve ser possivel cadastrar uma conta com CPF já existente

-[x] Não deve ser possivel depositar em uma conta não existente

-[x] Não deve ser possivel buscar extrato em uma conta não existente

-[x] Não deve ser possivel fazer saque em uma conta não existente

-[x] Não deve ser possivel excluir uma conta não existente

-[] Não deve ser possivel fazer saque quando o saldo for insuficiente
