# Matemática Discreta - Parte 2

Este repositório contém atividades desenvolvidas em C relacionadas aos temas de Grafos, Fechos e Princípio da Indução Finita (PiF).

---

# Atividade 6 - Número de Arestas de um Grafo Completo

## Objetivo

Calcular a quantidade de arestas de um grafo completo a partir do número de vértices informado pelo usuário.

## Relação com Matemática Discreta

A Teoria dos Grafos é uma área importante da Matemática Discreta.

Um grafo é formado por:

- Vértices (nós);
- Arestas (ligações).

Um grafo completo é aquele em que cada vértice está conectado a todos os outros vértices.

## Fórmula Utilizada

A quantidade de arestas de um grafo completo é dada por:

```
A = n(n - 1) / 2
```

Onde:

- A = quantidade de arestas;
- n = quantidade de vértices.

## Funcionamento

O programa solicita a quantidade de vértices e utiliza a fórmula matemática para calcular o número total de arestas.

## Como compilar

```bash
gcc grafo_completo.c -o grafo_completo
```

## Como executar

```bash
./grafo_completo
```

## Exemplo

```text
Digite a quantidade de vertices: 5

O grafo completo possui 10 arestas.
```

---

# Atividade 7 - Grau de um Vértice

## Objetivo

Determinar o grau de um vértice em um grafo.

## Relação com Matemática Discreta

Na Teoria dos Grafos, o grau de um vértice corresponde ao número de arestas conectadas a ele.

O conhecimento do grau dos vértices é utilizado em redes, rotas, conexões e análise de grafos.

## Funcionamento

O usuário informa quantas arestas estão conectadas ao vértice.

O programa realiza a contagem e apresenta o grau correspondente.

## Como compilar

```bash
gcc grau_vertice.c -o grau_vertice
```

## Exemplo

```text
Quantas arestas chegam ao vertice? 4

O grau do vertice e 4
```

---

# Atividade 8 - Fecho Reflexivo

## Objetivo

Gerar o fecho reflexivo de um conjunto.

## Relação com Matemática Discreta

Uma relação é reflexiva quando todos os elementos de um conjunto se relacionam consigo mesmos.

Exemplo:

```text
(1,1)
(2,2)
(3,3)
```

## Funcionamento

O usuário informa a quantidade de elementos do conjunto.

O programa gera os pares ordenados necessários para tornar a relação reflexiva.

## Como compilar

```bash
gcc fecho_reflexivo.c -o fecho_reflexivo
```

## Exemplo

```text
Quantidade de elementos do conjunto: 4

Fecho reflexivo:
(1,1)
(2,2)
(3,3)
(4,4)
```

---

# Atividade 9 - Fecho Simétrico

## Objetivo

Identificar o par necessário para formar o fecho simétrico de uma relação.

## Relação com Matemática Discreta

Uma relação é simétrica quando:

```text
Se (a,b) pertence à relação,
então (b,a) também pertence.
```

## Funcionamento

O usuário informa um par ordenado.

O programa exibe a relação original e o par necessário para garantir a simetria.

## Como compilar

```bash
gcc fecho_simetrico.c -o fecho_simetrico
```

## Exemplo

```text
Digite o primeiro elemento: 1
Digite o segundo elemento: 3

Relacao original: (1,3)
Par necessario para o fecho simetrico: (3,1)
```

---

# Atividade 10 - Soma dos N Primeiros Números Naturais

## Objetivo

Calcular a soma dos números naturais de 1 até N.

## Relação com Matemática Discreta

O Princípio da Indução Finita (PiF) é uma técnica de demonstração utilizada na Matemática Discreta.

Uma propriedade frequentemente demonstrada por indução é:

```text
1 + 2 + 3 + ... + n
```

## Funcionamento

O usuário informa um número inteiro positivo.

O programa realiza a soma de todos os números de 1 até o valor informado.

## Como compilar

```bash
gcc soma_naturais.c -o soma_naturais
```

## Exemplo

```text
Digite um numero inteiro positivo: 5

A soma de 1 ate 5 e 15
```
