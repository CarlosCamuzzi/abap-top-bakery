# Especificações do Projeto

Diante da análise do problema e da necessidade do cliente **Top Bakery**, foram levantados os seguintes requisitos:

## Requisitos Funcionais

| ID   | Descrição | Prioridade |
|------|-----------|-----|
| 001  | O sistema deverá permitir a criação de ordens de compra de insumos junto ao fornecedor. | ALTA |
| 002  | O sistema deverá permitir o registro das entradas de insumos. | MÉDIA |
| 003  | O sistema deverá permitir a precificação dos produtos finais. | MÉDIA |
| 004  | O sistema deverá permitir a geração de relatórios de vendas de produtos. | BAIXA |
| 005  | O sistema deverá permitir o cadastro de receitas. | ALTA |
| 006  | O sistema deverá permitir a geração da ordem de produção a partir das receitas. | MÉDIA |
| 007  | O sistema deverá permitir o cadastro de insumos. | ALTA |
| 008  | O sistema deverá permitir o cadastro de produtos finais. | ALTA |
| 009  | O sistema deverá permitir o registro da venda. | MÉDIA |
| 010  | O sistema deverá permitir a atualização do estoque de produtos. | MÉDIA |
| 011  | O sistema deverá permitir a atualização do estoque de insumos. | MÉDIA |
| 012  | O sistema deverá permitir o cadastro de funcionários. | ALTA |
| 013  | O sistema deverá permitir a geração de ordem de produção. | MÉDIA |
| 014  | O sistema deverá permitir a finalização de ordem de produção. | BAIXA |
| 015  | O sistema deverá permitir a geração de ordem de abastecimento. | BAIXA |
| 016  | O sistema deverá permitir a geração de relatórios de compras de insumos. | BAIXA |

## Requisitos Não Funcionais

| ID   | Descrição |
|------|-----------|
| 001  | O sistema deverá manter permissões de acesso diferentes para usuários distintos. |
| 002  | O sistema deverá ser desenvolvido em **ABAP**. |

## Matriz de Rastreabilidade

Diante dos requisitos funcionais levantados, foram analisadas as seguintes dependências:

| ID   | F001 | F002 | F003 | F004 | F005 | F006 | F007 | F008 | F009 | F010 | F011 | F012 | F013 | F014 | F015 | F016 | 
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
| F001 |      |      |      |      |      |      | X    |      |      |      |      |      |      |      |      |      |
| F002 | X    |      |      |      |      |      | X    |      |      |      |      |      |      |      |      |      |
| F003 |      |      |      |      |      |      |      | X    |      |      |      |      |      |      |      |      |
| F004 |      |      |      |      |      |      |      | X    | X    |      |      |      |      |      |      |      |
| F005 |      |      |      |      |      |      | X    | X    |      |      |      |      |      |      |      |      |
| F006 |      |      |      |      | X    |      |      |      |      |      |      |      |      |      |      |      |
| F007 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
| F008 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |
| F009 |      |      | X    |      |      |      |      | X    |      |      |      |      |      |      |      |      |
| F010 |      |      |      |      |      |      |      | X    | X    |      |      |      |      |      |      |      |
| F011 |      | X    |      |      |      |      |      |      |      |      |      |      | X    | X    |      |      |
| F012 |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      
| F013 |      |      |      |      | X    |      |      |      |      |      |      |      |      |      |      |      |      
| F014 |      |      |      |      |      |      |      |      |      |      |      |      | X    |      |      |      |     
| F015 |      |      |      |      |      |      |      | X    | X    |      |      |      |      |      |      |      |      
| F016 | X    | X    |      |      |      |      |      |      |      |      |      |      |      |      |      |      |      

### Considerações

#### Funcionalidades Base:
- **F007:** Cadastro de insumos<br>
- **F008:** Cadastro de produtos finais

#### Possíveis Gargalos:
- **F008** está envolvido nas dependências **F003, F004, F005, F009, F010, F015**<br>
- **F007** está envolvido nas dependências **F001, F002, F005**<br>
- **F009** está envolvido nas dependências **F004, F010, F015**

### Cadeia de Dependências Críticas:
- **Fluxo de produção:** F005 -> F013 -> F014<br>
- **Fluxo de vendas:** F008 -> F009 -> F010<br>
- **Fluxo de insumos:** F007 -> F002 -> F011 

[Baixar planilha da Matriz de Rastreabilidade](https://github.com/CarlosCamuzzi/abap-top-bakery/blob/main/docs/file/top_bakery_matriz_rastreabiidade.xlsx)

## Personas

As personas observadas dentro do contexto do projeto estão listadas abaixo:
- Cliente
- Fornecedor
- Vendedor
- Padeiro
- Repositor
- Supervisor
- Gerente

## Diagrama de Caso de Uso

De acordo com as personas e os requisitos levantados, foi criado o seguinte diagrama de caso de uso:

<img src="https://github.com/CarlosCamuzzi/abap-top-bakery/blob/main/docs/img/diagrama_caso_uso_bakery.png" alt="Top Bakery: Caso de Uso" width="500" height="722">
