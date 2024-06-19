# Banco-de-Dados

- Consultas do Projeto de Banco de Dados Parte 1
    1 - Mostre o nome e o endereço do cliente que indicou 'João da Silva'.
    2 - Liste o CNPJ, nome e email dos fornecedores que não tem home page
    cadastrados no sistema.
    3 - Qual foi a compra mais cara feita entre os clientes nascidos na década de 90 e
    residem em Campina Grande?
    4 - Quantas ordens de compra estão aguardando pagamento?
    5 - Quais os códigos das notas fiscais de valor entre 3000 e 10000 reais?
    6 - Qual o nome dos clientes que fizeram ordens de compra de valor entre R$ 500 e
    R$ 5000, moram em Campina Grande e possuem mais de 100 pontos?
    7 - Qual o nome dos produtos que foram fabricados em 2019, possuem preço de
    venda de pelo menos 2000 reais e data de vencimento para o ano de 2022 em diante?
    8 - Qual o nome das transportadoras que estão transportando ordens de compra com
    valor de frete acima de R$ 100,00?
    9 - Recupere o nome das categorias cujo preço médio dos produtos é maior que R$
    1.000,00.
    10 - Recupere o nome dos fornecedores cujo preço de venda médio dos seus
    produtos não é maior que R$ 163,00.
    11 - Liste os 3 fornecedores que mais forneceram produtos.

- Consultas do Projeto de Banco de Dados Parte 2
    1 - Implemente uma procedure PL/SQL chamada ajusta_preco. Esta procedure recebe
    o código de uma categoria e aplica um aumento de R$100,00 no preço (venda e
    compra) de todos os produtos da categoria informada.
    2 - Implemente uma função PL/SQL chamada get_total_prod_comprados. Esta função
    deverá receber uma data e retornar a soma dos valores dos produtos que foram
    comprados em uma data igual ou anterior a data recebida como parâmetro.
    3 - Implemente uma função PL/SQL chamada calcula_total_fornecedor. Esta função
    deverá receber o código do fornecedor e retornar o valor total da soma dos preços de
    compra dos produtos que foram fornecidos pelo fornecedor especificado.
    4 - Crie uma view que lista as ordens de compra no valor de mais de 10 mil reais que
    foram transportadas pela transportadora 'Azul Cargo'.
    5 - Crie uma view que lista as transportadoras e a quantidade compras que elas já
    transportaram.
    6 - Crie uma view que lista os fornecedores e a quantidade de produto por categoria
    fornecidos por eles. A view deve exibir os dados dos fornecedores, a categoria do
    produto e a quantidade de produtos por categoria.
    7 - Crie um trigger para modificar o nome da transportadora deixando a primeira letra
    no nome sempre maiúscula quando esse dado for inserido ou atualizado.
    8 - Crie um trigger para deixar em caixa alta todo o nome do cliente quando for
    inserido ou atualizado um número de CPF para ele.
    9 - Crie um trigger para substituir o valor do campo 'END_BAIRRO' por 'CENTRO' na
    tabela de CLIENTE se esse valor for nulo quando o cliente for atualizado ou inserido.
