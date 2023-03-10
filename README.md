K-means_algorithm_implementation
IFPE - Campus Recife - 2022.2 - TADS - Inteligência Artificial.
Atividade avaliativa da disciplina de IA: Implementação do Método K-Means.

Descrição:
  Este código implementa o algoritmo k-means, que é usado para agrupar pontos em k grupos 
baseados em suas coordenadas. O número de grupos (k) é definido pelo usuário. Inicialmente, 
são escolhidos aleatoriamente k pontos do conjunto de dados como centros iniciais. Em seguida, 
é feito o cálculo da distância de todos os pontos para cada centro, e os pontos são agrupados 
com base nas menores distâncias. Novos centros são calculados como a média dos pontos de cada
grupo e o processo é repetido até que não haja mais alterações no agrupamento dos pontos.
O código usa a biblioteca csv para ler e escrever em arquivos CSV, a biblioteca random para 
gerar números aleatórios, a biblioteca numpy para realizar cálculos matriciaise a biblioteca 
matplotlib.pyplot para plotar gráficos.
  A função "calcular_distancias" é usada para calcular a distância entre cada ponto em "kmeans.csv" e cada centro 
em "centros.csv". As distâncias são salvas em "distancias.csv". Em seguida, cada ponto é adicionado ao grupo
cujo centro tem a menor distância. Finalmente, a função retorna os pontos agrupados.
 Este código funciona com base de dados bidimensionais. 
  
