# Repositório de algoritmos de ordenação

## Sobre o Projeto
Este projeto tem como objetivo principal medir o tempo de execução dos algoritmos de ordenação, como parte de um artigo a ser publicado no Medium, vinculado à disciplina de Estrutura de Dados. O código base foi fornecido pelo professor da disciplina e posteriormente aprimorado por mim e meu colega de trabalho.

Uma função foi implementada para retornar o tempo em microssegundos que cada método leva para ordenar vetores de diferentes tamanhos e configurações. Para a medição do tempo, foi utilizada a biblioteca Chrono, disponível na linguagem C++, a qual permite uma medição precisa e confiável do tempo de execução de cada método de ordenação. Essa abordagem permitirá uma análise comparativa detalhada entre os algoritmos, fornecendo dados concretos para o artigo.

## Bibliotecas do c++ utilizadas
[vector](https://cplusplus.com/reference/vector/vector/ "vector")<br>
[random](https://learn.microsoft.com/pt-br/cpp/standard-library/random?view=msvc-170 "random")
[chrono](https://learn.microsoft.com/pt-br/cpp/standard-library/chrono-functions?view=msvc-170 "chrono")

## Algoritmos

## Bubble Sort
É um algoritmo de ordenação simples, este método percorre todo o vetor várias vezes, comparando cada elemento com seu vizinho, levando o maior elemento para o fim da sequência, fazendo isso n vezes até que o vetor esteja ordenado corretamente.
- Complexidade Computacional: A complexidade computacional do Bubble Sort é de O(n²) no pior caso e no caso médio. No melhor caso, quando a lista já está ordenada, a complexidade é de O(n).

## Selection Sort
Selection sort é um algoritmo de ordenação simples e intuitivo. Ele funciona selecionando repetidamente o menor (ou maior, dependendo da ordem desejada) elemento de uma lista não ordenada e movendo-o para o início da lista ordenada.
- Complexidade Computacional: A complexidade computacional do Selection Sort é de O(n²) no pior caso, no caso médio e no melhor caso.

## Insertion Sort
O insertion sort é outro algoritmo de ordenação simples, mas um pouco mais eficiente do que o selection sort em alguns casos. Ele funciona de forma semelhante à maneira como muitas pessoas ordenam cartas de baralho em suas mãos.
- Complexidade Computacional: A complexidade computacional do Insertion Sort é de O(n²) no pior caso e no caso médio. No entanto, no melhor caso, quando a lista já está ordenada, a complexidade é de O(n).

## Shell Sort
O shell sort é um algoritmo de ordenação mais avançado que tenta melhorar o desempenho do insertion sort ao tomar vantagem da ideia de que os elementos de uma lista que estão longe uns dos outros estão parcialmente ordenados.
- Complexidade Computacional: A complexidade computacional do Shell Sort depende do intervalo de lacunas (gaps) utilizado. No pior caso, a complexidade é de aproximadamente O(n²), mas pode variar dependendo da sequência de lacunas escolhida.

## Quick Sort
O quick sort é um dos algoritmos de ordenação mais eficientes e amplamente utilizados. Ele utiliza o método de divisão e conquista para ordenar uma lista de elementos. A ideia central do quick sort é selecionar um elemento, chamado de “pivô”, e particionar a lista em dois subconjuntos: um contendo elementos menores que o pivô e outro contendo elementos maiores que o pivô.
- Complexidade Computacional: A complexidade computacional do Quick Sort depende da escolha do pivô e da distribuição dos elementos no conjunto de dados. Em média, o Quick Sort tem uma complexidade de tempo de O(n log n), onde n é o número de elementos a serem ordenados. No pior caso, quando o pivô é sempre o menor ou o maior elemento da lista não ordenada, a complexidade pode ser de O(n²).

## Merge Sort
O merge sort é outro algoritmo de ordenação eficiente que utiliza a abordagem de divisão e conquista. Ele divide recursivamente a lista não ordenada em metades iguais, ordena cada metade separadamente e, em seguida, combina as duas metades ordenadas para produzir a lista final ordenada.
- Complexidade Computacional: A complexidade computacional do Merge Sort é sempre O(n log n), independentemente da distribuição dos elementos no conjunto de dados ou do tamanho da lista.

# Análise dos Resultados

Após a obtenção dos resultados, foi elaborada uma planilha no Excel para registrar os dados de desempenho de cada método de ordenação. Cada método foi executado cinco vezes, e a média dos tempos de execução foi calculada para uma análise mais precisa. Essa abordagem permitirá a identificação do método que apresenta o melhor desempenho em termos de tempo de execução.

Além disso, a comparação dos resultados obtidos permitirá a identificação das vantagens e desvantagens de cada algoritmo de ordenação. Essa análise detalhada contribuirá para uma melhor compreensão dos diferentes métodos e auxiliará na escolha do mais adequado para cada situação.
