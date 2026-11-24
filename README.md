# matematica-discreta-p2

# Atividade 6 - Número de Arestas de um Grafo Completo
<br>

## Objetivo

Calcular a quantidade de arestas de um grafo completo a partir do número de vértices informado pelo usuário.

<br>

## Relação com Matemática Discreta

A Teoria dos Grafos é uma área importante da Matemática Discreta.

Um grafo é formado por:

- Vértices (nós)
- Arestas (ligações)

Um grafo completo é aquele em que cada vértice está conectado a todos os outros vértices.

<br>

## Fórmula Utilizada

A quantidade de arestas de um grafo completo é dada por:

A = n(n - 1) / 2

Onde:

- A = quantidade de arestas
- n = quantidade de vértices

<br>

## Funcionamento

O programa solicita a quantidade de vértices e utiliza a fórmula matemática para calcular o número total de arestas.

<br>

## Como compilar

gcc grafo_completo.c -o grafo_completo

<br>

## Como executar

./grafo_completo

<br>

## Exemplo

Digite a quantidade de vertices: 5

O grafo completo possui 10 arestas.

<br>

# README - Atividade 7: Grau de um Vértice

# Atividade 7 - Grau de um Vértice ## Objetivo Determinar o grau de um vértice em um grafo. 

## Relação com Matemática Discreta Na Teoria dos Grafos, o grau de um vértice corresponde ao número de arestas conectadas a ele. O conhecimento do grau dos vértices é utilizado em diversos problemas envolvendo redes, rotas, conexões e análise de grafos. 

## Funcionamento O usuário informa quantas arestas estão conectadas ao vértice. O programa realiza a contagem e apresenta o grau correspondente. 

## Como compilar gcc grau_vertice.c -o grau_vertice

# Atividade 8 - Fecho Reflexivo
<br>

## Objetivo

Gerar o fecho reflexivo de um conjunto.

<br>

## Relação com Matemática Discreta

O estudo de relações é um dos tópicos centrais da Matemática Discreta.

Uma relação é reflexiva quando todos os elementos do conjunto se relacionam consigo mesmos.

Exemplo:

(1,1)

(2,2)

(3,3)

<br>

## Funcionamento

O usuário informa a quantidade de elementos do conjunto.

O programa gera automaticamente os pares ordenados necessários para que a relação seja reflexiva.

<br>

## Como compilar

gcc fecho_reflexivo.c -o fecho_reflexivo

<br>

## Como executar

./fecho_reflexivo

<br>

## Exemplo

Quantidade de elementos do conjunto: 4

Fecho reflexivo:

(1,1)

(2,2)

(3,3)

(4,4)

<br>

# Atividade 9 - Fecho Simétrico
<br>

## Objetivo

Identificar o par necessário para formar o fecho simétrico de uma relação.

<br>

## Relação com Matemática Discreta

Uma relação é simétrica quando:

Se (a,b) pertence à relação,

então (b,a) também pertence.

O fecho simétrico consiste em adicionar os pares necessários para garantir essa propriedade.

<br>

## Funcionamento

O usuário informa um par ordenado.

O programa exibe a relação original e o par que deve ser acrescentado para garantir a simetria.

<br>

## Como compilar

gcc fecho_simetrico.c -o fecho_simetrico

<br>

## Como executar

./fecho_simetrico

<br>

## Exemplo

Digite o primeiro elemento: 1

Digite o segundo elemento: 3

Relacao original: (1,3)

Par necessario para o fecho simetrico: (3,1)

<br>

# Atividade 10 - Soma dos N Primeiros Números Naturais
<br>

## Objetivo

Calcular a soma dos números naturais de 1 até N.

<br>

## Relação com Matemática Discreta

O Princípio da Indução Finita (PiF) é uma técnica de demonstração muito utilizada na Matemática Discreta.

Uma das propriedades frequentemente demonstradas por indução é:

1 + 2 + 3 + ... + n

cujo resultado pode ser calculado por:

n(n + 1) / 2

Nesta atividade, a soma é realizada por meio de repetições para ilustrar o processo.

<br>

## Funcionamento

O usuário informa um número inteiro positivo.

O programa soma todos os números de 1 até o valor informado e exibe o resultado.

<br>

## Como compilar

gcc soma_naturais.c -o soma_naturais

<br>

## Como executar

./soma_naturais

<br>

## Exemplo

Digite um numero inteiro positivo: 5

A soma de 1 ate 5 e 15

<br>

## Verificação Matemática

1 + 2 + 3 + 4 + 5 = 15

<br>
