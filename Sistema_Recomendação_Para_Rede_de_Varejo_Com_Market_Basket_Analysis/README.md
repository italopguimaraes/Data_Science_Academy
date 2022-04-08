# Sistema de Recomendação Para Rede de Varejo Usando Market Basket Analysis

Quer você faça compras com listas de compras meticulosamente
planejadas ou deixe que o capricho guie seus passos, nossos rituais únicos de
compra definem quem somos. Instacart, um aplicativo de pedido e entrega de
supermercado, tem como objetivo facilitar o preenchimento de sua geladeira e
despensa com seus itens pessoais favoritos e itens básicos quando você precisar
deles. Depois de selecionar produtos por meio do aplicativo Instacart, os
compradores revisam seus pedidos, fazem compras e a entrega é feita na loja
mais próxima a você.
A equipe de ciência de dados da Instacart desempenha um papel
importante no fornecimento dessa experiência de compra agradável. Atualmente,
eles usam dados transacionais para desenvolver modelos que preveem quais
produtos um usuário comprará novamente, quais tentará pela primeira vez ou
quais adicionará ao carrinho durante uma sessão. Recentemente, a Instacart
disponibilizou esses dados de forma aberta e o link para download você encontra
logo abaixo
Neste projeto de ciência de dados, você usará esses dados anônimos nos
pedidos dos clientes ao longo do tempo para prever quais produtos adquiridos
anteriormente estarão no próximo pedido de um usuário.
Nossa recomendação é que você utilize linguagem R e os pacotes de
Market Basket Analysis oferecidos em R. O link para download do dataset você
encontra aqui:
https://www.instacart.com/datasets/grocery-shopping-2017
Aqui você encontra um post do VP da Instacart definindo o problema em
detalhes:
https://tech.instacart.com/3-million-instacart-orders-open-sourcedd40d29ead6f2
Esse projeto é parte da Formação Cientista de Dados da Data Science Academy

## Dependências de Software

Tenha certeza que `jupyter-notebook`,`pandas`,`numpy`,`seaborn`,`matplotlib` e `fpgrowth_py` estão instalados:

`conda install pandas numpy seaborn matplotlib fpgrowth_py`

## Instruções do Projeto

1. Clone o repositório ou faça o download e navegue no diretório contendo o arquivo Sistema_Recomendação_Para_Rede_de_Varejo_Com_Market_Basket_Analysis, crie um diretório chamado dados baixe os arquivos: aisles.csv, departments.csv, order_products__prior.csv, order_products__train.csv, orders.csv, products.csv e sample_submission.csv na url: https://www.kaggle.com/c/instacart-market-basket-analysis/data, e coloque neste diretório dados;

2. Agora basta executar o notebook SupplyChain-Analytics-Mini-Projeto10.ipynb no jupyter notebook.
