Documentação do Código de Ordenação em C++
Este código em C++ implementa vários algoritmos de ordenação (Bubble Sort, Selection Sort, Insertion Sort, Shell Sort, Quick Sort e Merge Sort) e mede o tempo de execução de cada algoritmo para diferentes tamanhos de vetores.

Inclusões de Bibliotecas
#include <iostream>: Para entrada e saída padrão.
#include <vector>: Para usar vetores em C++.
#include <random>: Para geração de números aleatórios.
#include <chrono>: Para medir o tempo de execução dos algoritmos.
Espaços de Nomes Utilizados
using namespace std;: Para simplificar o uso de elementos do namespace std.
using namespace std::chrono;: Para simplificar o uso de elementos do namespace std::chrono.
Funções Implementadas
printArray(vector<int> &v): Função para imprimir os elementos de um vetor.
swap(int a, int b)**: Função para trocar o valor de duas variáveis.
bubbleSort(vector<int> &v): Implementação do algoritmo Bubble Sort.
selectionSort(vector<int> &v): Implementação do algoritmo Selection Sort.
insertionSort(vector<int> &v): Implementação do algoritmo Insertion Sort.
shellSort(vector<int> &v): Implementação do algoritmo Shell Sort.
partition(vector<int> &v, int low, int high): Função auxiliar para o Quick Sort.
quickSort(vector<int> &v, int low, int high): Implementação do algoritmo Quick Sort.
merge(vector<int> &v, int low, int high, int mid): Função auxiliar para o Merge Sort.
mergeSort(vector<int> &v, int low, int high): Implementação do algoritmo Merge Sort.
medir_BubbleSort(vector<int> &v): Função que mede e imprime o tempo de execução do Bubble Sort.
medir_SelectionSort(vector<int> &v): Função que mede e imprime o tempo de execução do Selection Sort.
medir_InsertionSort(vector<int> &v): Função que mede e imprime o tempo de execução do Insertion Sort.
medir_ShellSort(vector<int> &v): Função que mede e imprime o tempo de execução do Shell Sort.
medir_QuickSort(vector<int> &v): Função que mede e imprime o tempo de execução do Quick Sort.
medir_MergeSort(vector<int> &v): Função que mede e imprime o tempo de execução do Merge Sort.
Função Principal (main)
main(): Na função principal, são testados os algoritmos de ordenação para diferentes tamanhos de vetores preenchidos com números aleatórios.
Características Específicas do Código
Eficiência dos Algoritmos: Cada algoritmo de ordenação tem sua eficiência própria em termos de tempo de execução e uso de recursos.
Medição de Tempo: A medição de tempo é feita usando a biblioteca <chrono>.
Geração de Números Aleatórios: O código usa a biblioteca <random> para gerar números aleatórios.
Estabilidade dos Algoritmos: Os algoritmos implementados não são estáveis.
Melhorias Possíveis: Existem algumas melhorias que podem ser feitas para otimizar o código, como usar a passagem por referência constante (const vector<int> &v) nos parâmetros das funções.
Testes e Validação: O código realiza testes com diferentes tamanhos de vetores para avaliar o desempenho dos algoritmos.
Como Usar
Para usar os algoritmos de ordenação implementados e medir o tempo de execução, basta chamar as funções medir_BubbleSort, medir_SelectionSort, medir_InsertionSort, medir_ShellSort, medir_QuickSort e medir_MergeSort, passando um vetor de inteiros como parâmetro.
Conclusão
Este código é útil para entender e comparar diferentes algoritmos de ordenação em C++. Ele fornece uma base sólida para quem deseja aprender sobre algoritmos de ordenação e suas implementações em C++.





