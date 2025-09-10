# Análise do Mercado de E-commerce Brasileiro: Um Estudo de Caso com os Dados da Olist

Este projeto de Ciência de Dados foca na análise do mercado de e-commerce brasileiro, utilizando o vasto conjunto de dados de pedidos da Olist Store. O principal objetivo foi extrair insights acionáveis sobre o comportamento do cliente, a eficiência da logística e a satisfação do consumidor para informar decisões estratégicas de negócios.

O conjunto de dados, que cobre mais de 100.000 pedidos realizados entre 2016 e 2018, oferece uma visão completa da jornada do cliente, incluindo o status do pedido, custos (preço e frete), desempenho de entrega, localização de clientes e vendedores, e avaliações dos produtos.

# Perguntas de Negócio e Análises Realizadas
Para guiar a análise, respondi a uma série de perguntas-chave:

Desempenho Logístico: Qual a porcentagem de pedidos com atraso? A falha de não registrar a data de entrega para pedidos 
delivered foi verificada? 

Eficiência de Embalagem: Qual a dimensão máxima que uma caixa de transporte deve ter para atender a todos os produtos? 

Comportamento de Vendas: Os pedidos estão crescendo ao longo do tempo? Qual foi o mês com o maior volume de vendas? 

Satisfação do Cliente: Quais são as categorias de produtos com as melhores e piores notas de avaliação? 

Métricas de Entrega: Qual a média e o tempo máximo de entrega em dias? 

Impacto no Frete: O que mais influencia o custo do frete: o peso ou o tamanho do produto? 

Vendas e Receita: Quais são os produtos que geraram a maior receita? 

Distribuição e Volume de Pedidos: Qual é o tipo de pagamento mais comum? Quais estados têm o maior número de pedidos? 


# Principais Resultados e Insights

Atrasos e Entregas: 7.87% dos pedidos foram entregues com atraso. Uma falha no sistema foi identificada, com 8 pedidos 
delivered sem data de entrega registrada.

Dimensões de Produtos: Para atender a todos os produtos, uma caixa precisa ter as seguintes dimensões mínimas: Altura máxima de 105 cm, Largura máxima de 118 cm, Comprimento máximo de 105 cm e Peso máximo de 40.425 g.

Análise de Frete: O peso do produto (product_weight_g) tem uma correlação maior com o valor do frete (freight_value) (0.61) do que o volume (volume_cm3) (0.59), indicando que o peso é o fator mais influente no cálculo do frete.

Métricas de Pedido: O tempo médio de entrega é de 12 dias, com a entrega mais longa durando 209 dias. A média de pedidos por cliente é de 1.00, sugerindo um baixo índice de recompra. O estado de São Paulo (SP) registrou o maior número de pedidos, com 41.746.

Satisfação do Vendedor: Um ponto de atenção revelado pela análise é que 58.06% dos vendedores no dataset receberam pelo menos uma avaliação com nota menor que 2.

# Ferramentas e Metodologia
Este projeto foi desenvolvido utilizando 
Python, com as bibliotecas Pandas para manipulação e análise de dados, e Matplotlib para visualização.

# Inovação: Agente de IA para Análise de Dados

Para demonstrar a aplicação de novas tecnologias, criei e integrei um Agente de IA ao projeto. Este assistente, construído com a API da OpenAI, foi treinado para responder a perguntas sobre o dataset, tornando a fase de exploração de dados mais ágil e interativa. Isso permitiu extrair insights de forma conversacional, como a contagem de pedidos por dia da semana.
