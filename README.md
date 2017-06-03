# ILE Trabalho Final

Repositório criado para realização do trabalho final da Matéria Introdução às linguagens Estatísticas


Introdução às linguagens Estatísticas

# Exercício final

Professor Arthur Gouveia

Data de entrega: 19/06/2017


# O exercício

Você trabalha em uma empresa que vende suplementos agrícolas no atacado e os executivos desejam saber a situação das vendas em algumas dimensões. É sua tarefa
desenvolver um relatório simples demonstrando tais indicadores para o corpo executivo da sua organização.

Os dados estão em tabelas em um banco SQLite e em um arquivo CSV. No banco estão armazenados os dados dos clientes e os dados dos produtos; no arquivo pedidos.csv
estão armazenadas as vendas do ano de 2017.

Descrição dos dados:

# tb_clientes
- id_cliente: Um número único que identifica o cliente
- nom_cliente: O nome do cliente
- des_uf: Estado onde está localizado o cliente
- des_cnae: Descrição do ramo de atividade do cliente

# tb_produtos
- id_produto: Um número único que identifica o produto
- nom_produto: O nome do produto
- cat_produto: Categoria do produto
- val_produto: Preço unitário do produto

# pedidos.csv
- id_produto: Um número único que identifica o produto que foi adquirido
- id_cliente:Um número único que identifica o cliente que fez o pedido
- num_nf: Número da nota fiscal do pedido
- dia_pedido: Dia do pedido
- mês_pedido: Mês do pedido
- ano_pedido: Ano do pedido
- id_vendedor: Um número único que identifica o vendedor responsável pela venda
- qtd_vendida: Quantidade do produto que foi adquirida nessa venda


Você deverá escrever um programa que:

# Grupo 2 - Por UF

Faça um programa que:
1. Mostre a lista de UFs disponíveis
2. Peça para o usuário selecionar uma UF
3. Mostre a quantidade de vendas, de produtos vendidos e a receita total para a UF selecionado
4. Faça isso em loop até o usuário escolher uma opção para sair do programa
5. Ao final apresente os seguintes indicadores:

A - Quantidade de vendas por UF em ordem decrescente
B - Quantidade de produtos vendidos por UF em ordem decrescente
C - Receita de vendas por UF em ordem decrescente
