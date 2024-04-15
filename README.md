# Repositório de algoritmos de ordenação

## Sobre o Projeto
Este projeto tem como objetivo principal medir o tempo de execução dos algoritmos de ordenação, como parte de um artigo a ser publicado no Medium, vinculado à disciplina de Estrutura de Dados. O código base foi fornecido pelo professor da disciplina e posteriormente aprimorado por mim e meu colega de trabalho.

Uma função foi implementada para retornar o tempo em microssegundos que cada método leva para ordenar vetores de diferentes tamanhos e configurações. Para a medição do tempo, foi utilizada a biblioteca Chrono, disponível na linguagem C++, a qual permite uma medição precisa e confiável do tempo de execução de cada método de ordenação. Essa abordagem permitirá uma análise comparativa detalhada entre os algoritmos, fornecendo dados concretos para o artigo.

## Algoritmos
---
### Bubble Sort
É um algoritmo de ordenação simples, este método percorre todo o vetor várias vezes, comparando cada elemento com seu vizinho, levando o maior elemento para o fim da sequência, fazendo isso n vezes até que o vetor esteja ordenado corretamente.
- Complexidade Computacional: A complexidade computacional do Bubble Sort é de O(n²) no pior caso e no caso médio. No melhor caso, quando a lista já está ordenada, a complexidade é de O(n).

# Análise dos Resultados

Após a obtenção dos resultados, foi elaborada uma planilha no Excel para registrar os dados de desempenho de cada método de ordenação. Cada método foi executado cinco vezes, e a média dos tempos de execução foi calculada para uma análise mais precisa. Essa abordagem permitirá a identificação do método que apresenta o melhor desempenho em termos de tempo de execução.

Além disso, a comparação dos resultados obtidos permitirá a identificação das vantagens e desvantagens de cada algoritmo de ordenação. Essa análise detalhada contribuirá para uma melhor compreensão dos diferentes métodos e auxiliará na escolha do mais adequado para cada situação.
