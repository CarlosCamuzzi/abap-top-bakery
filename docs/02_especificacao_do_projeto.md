# Especificações do Projeto

Diante da análise do problema e da necessidade do cliente **Top Bakery**, foram levantados os seguintes requisitos:

## Requisitos Funcionais

| ID   | Descrição | Prioridade |
|------|-----------|-----|
| 001  | O sistema deverá permitir a criação de ordens de compra de insumos junto ao fornecedor. | MÉDIA |
| 002  | O sistema deverá permitir o registro das entradas de insumos. | MÉDIA |
| 003  | O sistema deverá permitir a precificação dos produtos finais. | BAIXA |
| 004  | O sistema deverá permitir a geração de relatórios de vendas de produtos. | BAIXA |
| 005  | O sistema deverá permitir o cadastro de receitas. | ALTA |
| 006  | O sistema deverá permitir a geração da ordem de produção a partir das receitas. | MÉDIA |
| 007  | O sistema deverá permitir o cadastro de insumos. | ALTA |
| 008  | O sistema deverá permitir o cadastro de produtos finais. | ALTA |
| 009  | O sistema deverá permitir o registro da venda direta ao cliente. | BAIXA |
| 010  | O sistema deverá permitir o registro da venda. | MÉDIA |
| 011  | O sistema deverá permitir a atualização do estoque de produtos. | MÉDIA |
| 012  | O sistema deverá permitir a atualização do estoque de insumos. | MÉDIA |
| 013  | O sistema deverá permitir o cadastro de funcionários. | ALTA |
| 014  | O sistema deverá permitir a geração de ordem de produção. | MÉDIA |
| 015  | O sistema deverá permitir a finalização de ordem de produção. | BAIXA |
| 016  | O sistema deverá permitir a geração de ordem de abastecimento. | BAIXA |
| 017  | O sistema deverá permitir a geração de relatórios de compras de insumos. | BAIXA |

## Requisitos Não Funcionais

| ID   | Descrição |
|------|-----------|
| 001  | O sistema deverá manter permissões de acesso diferentes para usuários distintos. |
| 002  | O sistema deverá ser desenvolvido em **ABAP**. |

## Matriz de Rastreabilidade

| Código  | Requisito | Prioridade | Funcionalidade | Caso de Teste | Status |
|:---------:|-----------|:------------:|---------------|--------------|:--------:|
| **001** | O sistema deverá permitir a criação de ordens de compra de insumos junto ao fornecedor. | MÉDIA | Tela de Ordens de Compra | CT001 - Criar ordem de compra | Pendente |
| **002** | O sistema deverá permitir o registro das entradas de insumos. | MÉDIA | Tela de Entrada de Insumos | CT002 - Registrar entrada de insumos | Pendente |
| **003** | O sistema deverá permitir a precificação dos produtos finais. | BAIXA | Tela de Precificação | CT003 - Definir preço do produto | Pendente |
| **004** | O sistema deverá permitir a geração de relatórios de vendas de produtos. | BAIXA | Tela de Relatórios | CT004 - Gerar relatório de vendas | Pendente |
| **005** | O sistema deverá permitir o cadastro de receitas. | ALTA | Tela de Receitas | CT005 - Cadastrar uma receita | Pendente |
| **006** | O sistema deverá permitir a geração da ordem de produção a partir das receitas. | MÉDIA | Tela de Produção | CT006 - Gerar ordem de produção | Pendente |
| **007** | O sistema deverá permitir o cadastro de insumos. | ALTA | Tela de Cadastro de Insumos | CT007 - Cadastrar um insumo | Pendente |
| **008** | O sistema deverá permitir o cadastro de produtos finais. | ALTA | Tela de Cadastro de Produtos | CT008 - Cadastrar um produto final | Pendente |
| **009** | O sistema deverá permitir o registro da venda direta ao cliente. | BAIXA | Tela de Vendas | CT009 - Realizar venda direta | Pendente |
| **010** | O sistema deverá permitir o registro da venda. | MÉDIA | Tela de Registro de Vendas | CT010 - Registrar uma venda | Pendente |
| **011** | O sistema deverá permitir a atualização do estoque de produtos. | MÉDIA | Tela de Estoque | CT011 - Atualizar estoque de produtos | Pendente |
| **012** | O sistema deverá permitir a atualização do estoque de insumos. | MÉDIA | Tela de Estoque | CT012 - Atualizar estoque de insumos | Pendente |
| **013** | O sistema deverá permitir o cadastro de funcionários. | ALTA | Tela de Funcionários | CT013 - Cadastrar funcionário | Pendente |
| **014** | O sistema deverá permitir a geração de ordem de produção. | MÉDIA | Tela de Produção | CT014 - Gerar ordem de produção | Pendente |
| **015** | O sistema deverá permitir a finalização de ordem de produção. | BAIXA | Tela de Produção | CT015 - Finalizar ordem de produção | Pendente |
| **016** | O sistema deverá permitir a geração de ordem de abastecimento. | BAIXA | Tela de Abastecimento | CT016 - Gerar ordem de abastecimento | Pendente |
| **017** | O sistema deverá permitir a geração de relatórios de compras de insumos. | BAIXA | Tela de Relatórios | CT017 - Gerar relatório de compras | Pendente |


## Personas

As personas observadas dentro do contexto do projeto são:
- Cliente
- Fornecedor
- Vendedor
- Padeiro
- Repositor
- Supervisor
- Gerente

## Diagrama de Caso de Uso

De acordo com os requisitos levantados, foi criado o seguinte diagrama:

<img src="https://github.com/CarlosCamuzzi/abap-top-bakery/blob/main/docs/img/diagrama_caso_uso_bakery.png" alt="Top Bakery: Caso de Uso" width="500" height="722">
