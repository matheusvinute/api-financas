## FinAPI - Financeiro

### `Requisitos`

-[x] Deve ser possível cirar uma conta
-[x] Deve ser possível buscar o extrato bancário do cliente
-[x] Deve ser possível realizar um depósito
-[x] Deve ser possível realizar saque
-[x] Deve ser possivel buscar o extrato bancário do cliente por data
-[] Deve ser possivel atualizar dados da conta do cliente
-[] Deve ser possivel obter dados da conta do cliente
-[] Deve ser possivel deletar uma conta

### `Regra de Negócio`

-[x] Não deve ser possivel cadastrar uma conta com CPF já existente
-[x] Não deve ser possivel depositar em uma conta não existente
-[x] Não deve ser possivel buscar extrato em uma conta não existente
-[x] Não deve ser possivel fazer saque em uma conta não existente
-[x] Não deve ser possivel excluir uma conta não existente
-[] Não deve ser possivel fazer saque quando o saldo for insuficiente