# Star_Schema

# Modelagem de dados - Star Schema

## [Estou aprendendo pelo Dio](www.dio.me)

Star Schema: O esquema em estrela é uma abordagem de modelagem madura amplamente adotada por data warehouses relacionais. Ele requer que os modeladores classifiquem suas tabelas de modelo como dimensão ou fato. Tabelas de dimensões descrevem as entidades de negócios – os itens que você modela.

Tabela fato - F_Vendas:
SK_ID , ID_Produto, Produto, Units Sold, Sales Price, Discount Band, Segment, Country, Salers, Profit, Date (campos)

Tabelas dimensão:
D_Produtos (ID_produto, Produto, Média de Unidades Vendidas, Médias do valor de vendas, Mediana do valor de vendas, Valor máximo de Venda, Valor mínimo de Venda)

D_Produtos_Detalhes(ID_produtos, Discount Band, Sale Price, Units Sold, Manufactoring Price)

D_Descontos (ID_produto, Discount, Discount Band)

D_Detalhes (*)

Calendário – Criada por DAX com calendar()
