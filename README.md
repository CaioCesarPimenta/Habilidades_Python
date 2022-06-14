# Habilidades_Python
 
Nesta pasta contem diferentes desafios que resolvi para poder mostrar minha habilidade com a linguagem python . irei explicar agora o que cada código faz em cada pasta .

-clientes devedores : dentro dessa pasta nos é dada um lista de tuplas onde cada tupla contem um cpf , um valor e uma quantidade de dias .
eu crio nesse código uma função onde colocamos um valor e uma quantidade em dias e se a pessoa estiver dentro desse limite em dias e devendo esse certo valor estipulado a função nos retorna a mensagem com o cpf , o quanto esta devendo e a quantidade em dias que se passaram .

-níveis de Co2 : neste código recebemos um dicionário . onde nos e dado a informações de estados brasileiros e 5 marcações feitas por censores de uma empresa.
a média dessas marcações nos diz o nível de Co2 ao longo de um certo tempo e estando maior do que um certo valor estipulado ele e considerado alto.
o código faz esses cálculos e nos retorna as cidades com o nível de Co2 alto e a quantidade de Co2 no local para ser considerada alta 

-crescimento do produto : aqui recebemos uma lista de tuplas contendo um produto , o lucro desse produto em 2019 e o lucro desse mesmo produto em 2020 respectivamente 
 esse código nos retorna a porcentagem em vendas que cada produto vendeu de um ano para o outro 

-identificação_por_código : aqui recebemos uma lista de códigos  de bebidas de um super mercado onde as bebidas alcoólicas possuem um certo padrão na escrita do cod .

meu cod identifica qual desses códigos são referentes a bebidas alcoólicas e quais não são.

Retornando uma mensagem avisando o código e para qual setor ela deve ser enviada 

-Stockout : A maioria das empresas tem suas próprias regras para cálculos de indicadores.

Algumas empresas definem que um cliente é considerado um cliente inadimplente quando ele está devendo acima de X reais e por mais de X dias.
 Algumas empresas definem que um vendedor bateu a meta quando ele vendeu acima de X reais (outras ainda analisam não só as vendas desse vendedor, mas também da loja ou da unidade de negócios que ele faz parte, ou ainda uma avaliação qualitativa)
Algumas empresas definem que um produto está em "falta" no estoque quando ele está abaixo de um nível mínimo quando um cliente insere um novo pedido daquele produto
E assim vai para dezenas de indicadores.

stockout é dado por (Vendas Perdidas por Estoque) / (Vendas Concluídas + Vendas Perdidas por Estoque) -> essas vendas são dadas em valor total (dinheiro) e não em quantidade de vendas

meu programa recebe um dicionário com todas as vendas da empresa, o status dela (se foi Concluída ou Cancelada) e, caso tenha sido Cancelada, o motivo de Cancelamento
