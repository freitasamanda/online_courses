# Aula 7 - Estatística Descritiva

Date: 05/11/2022

Aula 7 - Estatítica descritiva

# Aula 7 - Estatística descritiva

Uma série de medidas para descrever e resumir uma série de dados. Medidas que fornecem informações a respeito dos dados.
Frequência dos valores assumidos pela variável considerada -> frequência que pode ser absoluta ou relativa (isto é, a quantidade que cada valor diferente ocorre ou a proporção de ocorrências)

A estatística escolhida depende do que você quer resgatar ou destacar dos dados - que tipo de resumo fazemos. Na maioria dos trabalhos é bom mostrar as estatísticas descritivas antes de mostrar as análises mais complexas.  Ajuda também o próprio pesquisador a saber o que cada dado no banco representa (o que compõe cada variável, o que cada observação representa, quais os valores max e min que estão naquela variável, entre outras estats)

A primeira estatística seria a *frequência de ocorrência dos dados* - isto é, quantas vezes aqueles valores acontecem na variável (absoluta) ou número de vezes dividido pelo total, proporção que cada valor representa (relativa).

Variáveis contínuas é mais comum usar faixas de frequência do que quantidade que cada valor ocorre, que é mais comum em variáveis categóricas.

Um histograma é um gráfico que mostra as frequências relativas (eixo X são as variáveis e eixo Y são as freq relativas de cada intervalo que a variável assume) -> as áreas de cada intervalo somadas dão 1 ou 100% (essa propriedade é importante para entender probabilidade).

Intervalos no histograma são chamados de bin (Exemplo de 1 a 1, de 0,5 a 0,5). Quanto menor os bins, mais "espaços em branco" sobram. O bin a ser escolhido depende do tamanho da amplitude dos dados. Apesar de termos uma variável discreta, se ela pode assumir uma variedade muito grande de valores, a interpretação dela começa a se assemelhar a uma variável contínua e o histograma passa a não fazer sentido, ou criar categorias.Podemos por exemplo fazer uma *distribuição de kernel* com base num histograma (aproximar os pontos médios de frequências de cada um e traçar uma linha), que é usado por questõse analíticas, não porque a variável em si é contínua, mas porque analiticamente faz mais sentido tratá-la como tal - e esse tipo de decisão sempre tem consequências. Fazer isso se chama fazer uma *aproximação discreta-contínua*.

O gráfico para a variável contínua (com formato de sino, que usamos para entender o teorema do limite central, uma distribuição normal) também é um gráfico que mostra frequências relativas.  Existe uma fórmula que representa esse gráfico e veremos em próximas aulas. Existe uma fórmula matemática para gerar estes gráficos.

Dados podem ser assimétricos à esquerda ou à direita = dados concentrados com maior frequência em um dos lados do gráfico, ou em uma faixa de valores.

Saber o que está acontecendo com os dados permite que o pesquisador escolha um modelo que mais se adequa aos objetivos e os dados que eu tenho, as características muito específicas seja no fator gerador desses dados ou na distribuição que eles estão demonstrando (Exemplo do dado, jogo o dado e posso anotar os valores que saem no dado de diversas formas possíveis, preciso saber como o dado foi lançado, como foi anotado, qual critério foi usado e etc).

# MEDIDAS DE POSIÇÃO

São aquelas que indicam uma medida central considerando a magnitude dos valores, indica uma medida central de um conjunto de dados.

- média
- mediana = a mediana é o valor no ponto que divide a série de dados ao meio (50%). Lembrando que se tiver número par, por exemplo se forem 10 observações você pega o valor que esteja entre o 5o e o 6o elemento.
- moda = o valor que é mais frequente na série de dados.
- percentis = 25%, 75% são outros importantes (quartis), dividindo os valores em porcentagens.

Com dados assimétricos, a média não é igual à mediana, como na distribuição normal. A média vai ser influenciada pelos valores mais extremos, para a mediana a magnitude dos valores importa menos. Se eu adicionar mais observações, a mediana vai se mexer, mas as alterações nela são menos sensíveis do que a média, a média é mais sensível do que a magnitude do valor. A média é mais sujeita aos valores outliers do que a mediana, e isso pode influenciar que em algumas análises se use a mediana do que a média.

Essas medidas não dizem tudo porque podemos ter séries cujos valores sejam muito diferentes mas elas tenham a mesma média, mediana etc.

As medidas de posição são medidas de primeiro momento.

# MEDIDAS DE DISPERSÃO

Entender como os valores se distribuem em torno dessa posição central.
As medidas de dispersão são aquelas que indicam a magnitude da variação ou dispersão dos valores em torno de um valor típico.

- amplitude -> a distância entre o valor máximo e o mínimo
- variância -> como o dado está disperso em torno da média, compara-se cada dado com a média variância é o somatório da diferença entre cada valor (xi) e a média (individualmente, calculando a variação de cada um em relação à média, você consegue ver quanto cada um dos dados individualmente influênciou a variância). Se eu somo tudo e não elevo ao quadrado, vai dar 0, por causa dos números negativos. No final, divide por n, é a variância por unidade. Quando aparece com n-1 é uma estimativa da variância da POPULAÇÃO
- desvio padrão -> a unidade da variância é sempre ao quadrado. Então para arrumar nós tiramos a raiz da variância, que é o desvio padrão.
- IIQ (intervalo inter-quartil) -> valor do 3o quartil diferença do 1o quartil; ou 25% e 75%. Num boxplot ele aparece.