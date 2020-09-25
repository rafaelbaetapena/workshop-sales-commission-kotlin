# workshop-sales-commission-kotlin

Sistema de cálculo de comissão de vendas desenvolvido para estudo prático do kotlin.

## Regras de negócio - Parte 1

Como Gerente do setor de vendas preciso realizar o cálculo da comissão de uma venda. 

Uma venda é realizada por apenas um vendedor que irá receber a comissão de cada uma das vendas realizadas. 

Cada venda possui um vendedor responsável pela venda, data da realização da venda, uma lista de itens da venda, o cliente que realizou a compra e a forma de pagamento. 

Cada item da venda possui o produto vendido, quantidade do produto, preço unitário e subtotal do valor do item. 

As formas de pagamento podem ser por dinheiro, cartão de débito ou cartão de crédito e a venda pode ser paga utilizando mais de um método de pagamento.

A comissão total da venda é calculada a pelo valor do subtotal de cada item da venda aplicando um percentual de comissão daquele item de acordo com o seu produto.

O percentual de comissão da cada item de venda é definido de acordo com o fornecedor do produto, categoria do produto e produto, sendo possível definir um percentual de comissão apenas por fornecedor, um percentual de comissão apenas por fornecedor e categoria do produto e um percentual de comissão por fornecedor, categoria do produto e produto. O percentual de comissão também pode varia de acordo com a quantidade de produtos vendidos em um mesmo item de venda, sendo possível definir um percentual sem limite de quantidade.

Após o cálculo da comissão, deve ser possível extrair um relatório de comissão por venda que exiba o subtotal de comissão por item da venda e o total de comissão por venda e um relatório de comissão do mês por vendedor.
