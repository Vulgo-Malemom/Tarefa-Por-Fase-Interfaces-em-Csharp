## Caso 1 — Codificação de Mensagem

**Objetivo:** Proteger o conteúdo de uma mensagem antes de transmiti-la ou armazená-la.  
**Contrato:** Transformar o texto original em uma versão codificada.  
**Implementação A:** Codificar o texto em Base64.  
**Implementação B:** Aplicar cifra de César com 3 caracteres de deslocamento.  
**Política:** ?  
**Risco/Observação:** ?  


## Caso 2 — Ordenação de Coleções

**Objetivo:** Organizar uma lista de números ou objetos para facilitar busca, visualização ou processamento.  
**Contrato:** “Ordenar a coleção em ordem crescente”.  
**Implementação A:** Ordenação por Bubble Sort.  
**Implementação B:** Ordenação por Quick Sort.  
**Política:** Para listas pequenas Bubble Sort; para listas médias ou grandes QuickSort.  
**Risco/Observação:** BubbleSort é lento em listas grandes; QuickSort tem pior caso custoso em dados quase ordenados.
