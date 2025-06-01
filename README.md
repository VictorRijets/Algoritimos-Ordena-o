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
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

  
