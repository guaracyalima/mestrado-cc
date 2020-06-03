# Complexidade e analise de algoritimos (ou projeto e analise de algoritimos)

## Algoritimos
- É um procedimento computacional bem definido, que recebe um conjunto de valores como entrada e produz um conjunto de valores como saida.

- É uma ferramenta para resolver problemas computacionais

### Problema e Instância
- Um problema é definido por:
  - Uma descrição de parametros
  - Uma descrição sobre as propriedades quea resposta deve satisfazer

- Uma instância de um problema é obtida ao fixar valores para todos os parametros do prblema

### Corretude do algoritimo

Um algoritimo é correto (resolve o problema) se, para toda instância de entrada, o algoritimo termina e produz uma saida que satisfaz as propriedades do problema

O primeiro passo é mostrar que o algoritimo de fato resolve o prblema, isto é, mostrar que ele faz o que promete

**Prova de correção do algoritimo**
- Para algoritimos iterativos é usada a *técnica dos invariantes do laço*

- Para algoritimos recursivos é usada a *indução matematica* no tamanho das instâncias

### Consumo de tempo

Após provar se o algoritimo está correto podemos analisar o consumo de tempo do algoritimo. Para isso vamos estimar quanto tempo a maquina vai gastar ou quanto de memória será necessária para resolver a uma instância do problema

**Ordenação por inserção**

Até a posição `j-1` o vetor está ordenado e vamos tentar inserir o valor que está na posição `j` no lugar correto.
