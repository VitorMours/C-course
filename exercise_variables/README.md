# Trabalhando com variáveis e comentários em C 

**Variáveis** são uma forma de alorcamos a um determinado espaço fixo da memória, um valor que 
somente será modificado, se for necessário, por meio de uma operação no mesmo. Esse valor 
permanece estático até a finalização do programa, e pode ser acessado para uso do mesmo a 
qualquer momento do programa;

Por outro lado, temos que ** comentários ** podem ser entendidos como um tipo de instrução que 
nos permite adicionar conteúdo dentro do nosso código, sem alterar o comportamento do nosso 
código, pois o mesmo vai ser ignorado pelo compilador na hora de construir o nosso programa.

Esses tópicos possuem diversas informações dentro delas, que podem ser detalhadas com mais 
cuidado, como será mostrado a seguir:


## Comentários 
Os comentários dentro das linguagens de programação, são muito úteis por proporcionar uma forma 
de guardarmos informações úteis, mas que não serão executadas pelo compilador do nosso código. 
Um exemplo de uso, é que quando trabalhamos com sistemas de versionamento, como o git, 
podemos usar os comentários para nos comunicarmos com os outros desenvolvedores de maneira 
rápida, dentro do próprio código. 

Os comentários podem ser feitos dentro da linguagem C de duas formas, da forma de linha única,
e da forma de multilinha, como serão mostrado a seguir:


```C 
#include <stdio.h>

int main(){

    // Criando comentário de linha única dentro da linguagem C 

    /* Criando comentários de linha múltiplas
    * esse tipo de comentário costuma ser usado
    * para escrever documentação da linguagem,
    * e costuma seguir o padrão das Javadoc
    * */

    return 0;
}
```


## Variáveis
