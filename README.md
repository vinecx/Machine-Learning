Neste repositório de Machine Learning e Classificação, analisaremos quatro projetos e conjuntos de dados diferentes, sobre os quais tentaremos classificar informações em duas categorias distintas — isto é, usaremos algoritmos de machine learning para classificação, estimadores capazes de analisar a imagem de um animal e conseguir afirmar que se trata de um porco ou cachorro. Trata-se de um exemplo simples para que possamos introduzir o conceito de classificação e seu processo de estudo, treino e teste.

Um dos projetos é analisar se usuários que acessaram determinadas páginas de um site irão ou não comprar um produto específico. Então, estamos classificando entre duas opções de classes: "comprar ou não comprar", "sim" e "não", ou numericamente falando, "0" ou "1".

Outro projeto envolve duas features: imagine que queremos criar um blog ou site, mas não temos os conhecimentos necessários para fazer isso de forma autônoma. Então solicitamos que um aplicativo ou serviço qualquer nossos projetos e fazermos estimativas, por exemplo: o site demorará 42 horas para ser feito e queremos pagar 275,00 reais.

		
| unfished   | expected_hours       | price                           |
| :---------- | :--------- | :---------------------------------- |
| 1 | 26 | 192 |
| 1 | 88 | 9015 |
| 1 | 89 | 2577 |
| 1 | 42 | 275 |
| 1 | 39 | 170 |


Os dados que criamos para analisar o projeto representam o número de horas esperadas e o preço que um cliente está disposto a pagar por determinada tarefa, e queremos saber se algum desenvolvedor vai ou não realizar o trabalho.

Temos novamente um problema de classificação, mas dessa vez "horas esperadas" e "preço" são duas dimensões (features) que precisamos trabalhar. Conseguiremos visualizar essa informação de diversas maneiras diferentes, inclusive, entendendo como o algoritmo realiza as decisões dos projetos que serão ou não executados.

Por fim, teremos um projeto cujo foco da análise é a venda de alguns carros; a ideia é descobrirmos se determinados carros serão vendidos ou não com base no preço de cada um. Dessa forma, quando um cliente decide anunciar seu carro em site, podemos sugerir uma faixa de preço que facilitará o processo de venda.

Bolaremos maneiras de ilustrar o processo de classificação e então executá-lo cada vez de uma maneira diferente, com uma complexidade diferente.
