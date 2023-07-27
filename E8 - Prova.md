2022-10-31
[[Estrutura de Dados]]

---
#Univesp #C 

8. Analise a matriz de adjacência a seguir:  
  
  
0 1 0 0 0 0 0 0 0 0  
0 0 1 1 0 0 0 0 0 0   
0 0 0 0 1 1 0 0 0 0  
0 0 0 0 0 0 1 1 0 0  
0 0 0 0 0 0 0 0 1 1  
0 0 0 0 0 0 0 0 0 0   
0 0 0 0 0 0 0 0 0 0   
0 0 0 0 0 0 0 0 0 0   
0 0 0 0 0 0 0 0 0 0   
0 0 0 0 0 0 0 0 0 0  
  
Sobre a matriz apresentada, é possível afirmar:

A) as relações entre os nós do respectivo grafo só podem ser representadas pela árvore binária de busca, pois os ponteiros para as subárvores devem estar contidos na classe que descreve o nó, e não em uma matriz de adjacência externa.  
  
B) a matriz representa um grafo sem ciclos, mas não pode ser chamado de árvore porque é um grafo direcionado, ou seja, é um grafo em que a aresta apresenta a direção do caminho de um nó ao outro, não sendo permitido o caminho de volta.  
  
C) a matriz pode representar um grafo direcionado de uma árvore binária de busca balanceada, caso seja definido o vértice 1 como vértice inicial. Isso ocorre porque cada nó está ligado a, no máximo, dois outros nós, garantindo que o fator de balanceamento de cada nó seja igual a zero.  
  
D) as relações entre os nós do respectivo grafo seriam melhor representadas por meio de lista de adjacências, pois a matriz é esparsa e o grafo é direcionado. A lista de adjacência tem, ainda, a vantagem de eliminar a necessidade de guardar os valores de referência dos nós.  
  
CORRETA  
**E) a matriz representa um grafo de uma árvore binária, pois não tem ciclos e cada nó está ligado a, no máximo, duas subárvores. Não é possível afirmar que seja uma árvore binária de busca, pois os valores dos nós não estão representados na matriz de adjacências.**  
  
Semana: **Semana 6** / Nível de Dificuldade: **Difícil**  
Material Base: **Videoaula 17 - Grafos; e Videoaula 18 - Grafos (continuação) Páginas: Material completo**  
  
Objetivo de Aprendizado:  
**ANALISAR O PODER DE REPRESENTAÇÃO DE UMA MATRIZ DE ADJACÊNCIA**

---

_JUSTIFICATIVA DA RESPOSTA CORRETA**  
  
_O grafo representado é direcionado. Podemos identificá-lo facilmente, pois cada nó de número X só tem adjacência representada na matriz a outro nó de número Y, tal que X < Y. Ou seja, não há representação do caminho de volta da adjacência. Podemos ver que representa uma árvore, pois, além de cada nó de número X só ter adjacência representada na matriz a outro nó de número Y, tal que X < Y, também podemos observar que não há coincidência de valores 1 nas colunas. Ou seja, não há dois caminhos que levam ao mesmo nó. A árvore é binária porque cada nó está ligado pela adjacência na matriz a, no máximo, dois outros nós._

