# Arquitetura da Solução

## Diagrama de Fluxo

Diante do estudo dos requisitos, foram levantados os seguintes fluxos:

### Cadastro de Pessoa

<img src="https://github.com/CarlosCamuzzi/abap-top-bakery/blob/main/docs/img/flow_top_bakery_cadastro_pessoa.png" height="200">

### Cadastro de Insumo

<img src="https://github.com/CarlosCamuzzi/abap-top-bakery/blob/main/docs/img/flow_top_bakery_cadastro_insumo.png" height="200">

### Cadastro de Produto

<img src="https://github.com/CarlosCamuzzi/abap-top-bakery/blob/main/docs/img/flow_top_bakery_cadastro_produto.png" height="200">

### Ordem de Compra

<img src="https://github.com/CarlosCamuzzi/abap-top-bakery/blob/main/docs/img/flow_top_bakery_ordem_de_compra.png" height="200">

### Registro de Entrada de Insumos

<img src="https://github.com/CarlosCamuzzi/abap-top-bakery/blob/main/docs/img/flow_top_bakery_entrada_insumos.png" height="200">

### Cadastro de Receitas

<img src="https://github.com/CarlosCamuzzi/abap-top-bakery/blob/main/docs/img/flow_top_bakery_cadastro_receita.png" height="200">

### Ordem de Produção

<img src="https://github.com/CarlosCamuzzi/abap-top-bakery/blob/main/docs/img/flow_top_bakery_ordem_producao.png" height="200">

### Finalização de Ordem de Produção

<img src="https://github.com/CarlosCamuzzi/abap-top-bakery/blob/main/docs/img/flow_top_bakery_finalizar_ordem_producao.png" height="200">

### Precificação

<img src="https://github.com/CarlosCamuzzi/abap-top-bakery/blob/main/docs/img/flow_top_bakery_precificacao.png" height="200">

### Registro de Vendas

<img src="https://github.com/CarlosCamuzzi/abap-top-bakery/blob/main/docs/img/flow_top_bakery_venda.png" height="200">

### Ordem de Abastecimento

<img src="https://github.com/CarlosCamuzzi/abap-top-bakery/blob/main/docs/img/flow_top_bakery_ordem_abastecimento.png" height="200">

### Criação de Relatórios

<img src="https://github.com/CarlosCamuzzi/abap-top-bakery/blob/main/docs/img/flow_top_bakery_relatorios.png" height="200">

## Modelo Entidade Relacionamento

### Pessoa

- O modelo entidade relacionamento extendido foi utilizado, devido à entidade Pessoa.
- A entidade Pessoa assume vários papéis, sendo a entidade disjunta e total. Ou seja, é obrigatório ter uma entidade Pessoa e essa só pode ser de um tipo.
- Para simplificar a visualização desse relacionamento, abaixo segue diagrama separado.

<img src="https://github.com/CarlosCamuzzi/abap-top-bakery/blob/main/docs/img/modelo-er-pessoa.png" height="200">

### Modelo ER

![modelo er: modelagem entidade relacionamento](https://github.com/CarlosCamuzzi/abap-top-bakery/blob/main/docs/img/modelo-er-top-bakery.drawio.png)

## Esquema Relacional
