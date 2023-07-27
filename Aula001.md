
   Autor: Joao
   Tema: Programação Orientada a Objetos
   Subtema: C++
   Tags: #Univesp #C 
   


[[2023-07-24]]
[[002 - UNIVESP 🎓/Estrutura de dados/Aula002]]

# Anotações de aula

#### Comando de repetição:
- [ ] Estudar o comando "_while_"
	O While normalmente está no começo do bloco de programação. Então o comando primeiro verifica para executar.

- [ ] Comando "_For_"
	Outro comando de repetição

- [ ] Comando "_do"_
	Sempre vai aparecer o _while_ no final
	ele lê o bloco de programação até o _while_

- [ ] Estudar passagens por ==valor== ou por ==parâmetro==


#### Sintaxe Basica

1. Operações Matemáticas  
2. Comandos Condicionais
3. Comandos de Repetição
4. Declarações de Funções

##### Operações matemáticas
_O exemplo abaixo contem vários exemplos de operações matemáticas:_

``` C++
#include <iostream>  

// ************ Comentarios: ***********  
// Se eu usar a linha  
// using namespace std;  
// nao será necessario colocar o std antecedendo o out ou o in ou qualquer outro. Já fica implícito o std::xx  
  
int number1;  
int number2;  
int main() {  
std::cout << "Digite o primeiro numero: ";  
std::cin >> number1;  
std::cout << "Digite o segundo numero: ";  
std::cin >> number2;  
  
int sum = number1 + number2;  
std::cout << "Total soma: " << sum <<std::endl;  
int sub = number1 - number2;  
std::cout << "Total subtracao: " << sub <<std::endl;  
int mult = number1 * number2;  
std::cout << "Total multiplicacao: " <<mult <<std::endl;  
int div = number1 / number2;  
std::cout << "Total Divisao: " << div <<std::endl;  
float fdiv = (float)number1 / (float)number2;  
std::cout << "Total Divisao Float: " <<fdiv <<std::endl;  
int res = number1 % number2;  
std::cout << "Total Resto: " <<res <<std::endl;  
return 0;  
  
// ********** cuidado para nao colocar nada apos o return 0; ********  
  
}
```

---


##### Comandos condicionais
```c++

int number1;  
int number2;  
int main() {  
std::cout << "Digite o primeiro numero: ";  
std::cin >> number1;  
std::cout << "Digite o segundo numero: ";  
std::cin >> number2;  

if (number1 == number2) cout << number1 << " == " << number2 << std::endl;


````

---

##### Comandos de repetição
```c++




````
