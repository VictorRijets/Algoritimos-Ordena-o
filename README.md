# Implementação dos Algoritimos 

# Selection Sort

° Explicaçao:

 O Selection Sort (ou ordenação por seleção) é um algoritmo de ordenação simples e fácil de entender, que funciona da seguinte forma:
 Ele percorre a lista procurando o menor valor e o coloca na primeira posição. Depois procura o segundo menor e coloca na segunda posição. E assim por diante... até a lista estar ordenada.

 ° Pontos Positivos
 
   1. Simples de entender e implementar
      O algoritmo é direto: procura o menor valor e coloca no lugar certo.

   2. Poucas trocas (swaps)
      Mesmo que compare bastante, ele só troca quando necessário (no máximo uma vez por posição).

   3. Não precisa de memória extra (in-place)
      Ele organiza a lista sem precisar criar outra lista, economizando memória.
      
 ° Pontos Negativos

   1. Lento para listas grandes
      Complexidade é O(n²), ou seja, fica bem devagar com muitos elementos.

   2. Ignora se a lista já está quase ordenada
      Mesmo se a lista estiver quase no jeito, ele ainda faz todas as comparações.

   3. Não é estável (por padrão)
    Se dois valores forem iguais, ele pode trocar a ordem deles na lista final — isso pode ser ruim em alguns contextos (tipo ordenação por nome e idade).      
#
# Bubble Sort

°Explicação:

O Bubble Sort (ou ordenação por bolha) é um algoritmo simples que funciona comparando pares de elementos vizinhos e trocando-os de lugar se estiverem na ordem errada. Esse processo se repete várias vezes até que a lista esteja ordenada.
O nome "bolha" vem da ideia de que os valores maiores "sobem" para o final da lista a cada passada, como uma bolha subindo na água.

° Pontos Positivos

 1. Muito fácil de entender e implementar
    Ideal pra quem tá começando com algoritmos.

 2. Pode parar antes do final se a lista já estiver ordenada
    Dá pra otimizar com uma flag pra detectar se houve troca.

 3. Estável
    Mantém a ordem dos elementos iguais (importante em ordenações por múltiplos critérios).

° Pontos Negativos

  1. Muito lento em listas grandes
     Tem complexidade O(n²) — compara e troca muito.

  2. Faz muitas trocas desnecessárias
     Troca quase toda hora, mesmo se a lista estiver quase ordenada.

  3. Pouco usado na prática
     Só é bom pra estudo; na vida real, algoritmos melhores são preferidos.   
                 


  
