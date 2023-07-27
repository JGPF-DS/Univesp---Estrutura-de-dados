2022-10-31
[[Estrutura de Dados]]

---
#Univesp #C 

7. A busca por largura tem por objetivo pesquisar primeiro os nós mais próximos da raiz. É implementada com uma fila de nós marcados para a pesquisa. Quando o algoritmo enxerga nós ainda não pesquisados, coloca-os na fila. Quando os pesquisa, retira-os da fila, marcando-os como "pesquisados", para evitar ciclos infinitos. No entanto, podemos querer exatamente encontrar ciclos dentro do grafo por meio da busca por largura. Basta pedir que o algoritmo pare ao encontrar um nó já pesquisado.  
  
  
Sobre essa tentativa de uso da busca por largura como implementada em aula, identifique se são (V) verdadeiras ou (F) falsas as afirmativas a seguir.  
  
I. A busca por largura encontraria sempre o menor ciclo, se existir um ciclo.  
II. A busca por largura encontraria sempre o maior ciclo, se existir um ciclo.  
III. A busca por largura, na implementação de fila, não seria capaz de apresentar o ciclo como respostas, embora fosse capaz de encontrá-lo.  
IV. A busca por largura em um grafo não direcionado retornaria um ciclo já no segundo nó visitado.  
  
Assinale a alternativa que apresenta a sequência correta.

A) V, V, V, F.  
  
B) F, V, V, F.  
  
CORRETA  
**C) F, F, V, V.**  
  
Você marcou a alternativa ERRADA  
**D) V, F, V, F.**  
  
E) F, V, F, V.  
  
Semana: **Semana 7** / Nível de Dificuldade: **Difícil**  
Material Base: **Videoaula 20 - Grafos (PageRank) Páginas: Material completo**  
  
Objetivo de Aprendizado:  
**ANALISAR A UTILIDADE DA BUSCA POR LARGURA EM CASO EXEMPLIFICADO**

---

___**JUSTIFICATIVA DA RESPOSTA CORRETA**  _
  
_As afirmativas I e II são falsas, pois a busca por largura não pode garantir o maior ou menor ciclo, pois encontra o mais próximo. O maior ou o menor podem estar longe do nó inicial. A afirmativa III é verdadeira, pois, na implementação de aula, os itens são removidos da fila ao serem pesquisados. Não há, portanto, gravação do caminho já percorrido. A afirmativa IV é verdadeira, pois, em um grafo não direcionado, o nó raiz que direcionasse a, ao menos, um outro nó seria marcado como visitado. Mas o segundo nó teria, invariavelmente, uma ligação com o nó raiz (por ser não direcionado, a aresta tem ida e volta). Logo, esse segundo nó levaria a um nó visitado, causando o fim do algoritmo._
