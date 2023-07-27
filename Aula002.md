
   Autor: Joao
   Tema: Programação Orientada a Objetos
   Subtema: C++
   Tags: #Univesp #C 


[[2023-07-25]]
[[002 - UNIVESP 🎓/Estrutura de dados/Aula001]]

# Anotações de aula

#### Como declarar variáveis
- Pagina 09
```C++
int alpha;
int * intPointer;

```

#### Inicializar um ponteiro
- Pagina 09
Com base na informação anterior:
```C++
intPointer = &alpha;

```


#### Declaração de ponteiros
Usa-se a seguinte sintaxe:
tipo * ponteiro;

_Tipo_: refere-se para qual tipo de dados o ponteiro está apontando.
_Ponteiro_: é o nome da variável.

Se o tipo apontar para uma região de memória onde voce vai armazenar um tipo inteiro.
````Exemplo: 
int * a
"a" é uma variável do tipo inteiro para ponteiro.
Ela aponta para variaveis do tipo inteiro.
````
_O * indica que está apontando, ou seja, é um ponteiro_.

#### Tipos de alocação de memória
__Como obter um endereço de memória?__
O Endereço de uma variável de memória (ou função)
É a localização na memória do primeiro byte ocupado por ela.

de _maneira estática_ ou seja em tempo de compilação
de _maneira dinâmica_, ou seja, em tempo de execução.

- O operador _"&"_ nos permite obter o endereço de memória de uma variável. Feito isso, podemos inicializar um ponteiro.

###### Exemplo de alocação de memória dinâmica
```C++
int *intPointer;
intPointer = new int;

```


#### Alocar e desalocar memoria
Usar os operadores _"new"_ e _"delete"_ .
Toda vez que alocar a memoria será necessario desalocar.
No caso de variáveis alocadas estaticamente, não é necessário se preocupar. Preocupar-se apenas com aquelas variáveis que voce mesmo alocou.

- [ ] Alocação estática ou alocação dinâmica
