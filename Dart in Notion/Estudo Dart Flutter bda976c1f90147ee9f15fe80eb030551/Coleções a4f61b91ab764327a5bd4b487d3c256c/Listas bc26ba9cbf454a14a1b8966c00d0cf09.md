# Listas

[https://www.treinaweb.com.br/blog/manipulando-listas-no-dart](https://www.treinaweb.com.br/blog/manipulando-listas-no-dart)

Uma lista é a estrutura de dados mais básica do [Dart](https://www.treinaweb.com.br/blog/o-que-e-dart/). Sua estrutura permite armazenar dados em sequência, onde cada elemento possui sua posição de origem, sendo o primeiro elemento armazenado no índice zero e, a cada elemento novo, o índice é incrementado. Com o Dart, há diversos métodos para manipulação de listas

## Declaração de uma Lista

![Untitled](Listas%20bc26ba9cbf454a14a1b8966c00d0cf09/Untitled.png)

Uma lista também pode ser do tipo dinâmica que pode ser explicita ou implícita:

## Exemplo de uma lista dynamic:

![Untitled](Listas%20bc26ba9cbf454a14a1b8966c00d0cf09/Untitled%201.png)

## Funções

Dentro das Listas existe vaias funções, como por exemplo: 

- **add** para adicionar um item na lista
- **addAll** que adiciona uma listas de elementos na sua lista
- **insert** que adiciona um item na lista na posição que deseja
- **contains** que verifica na lista se contem o que foi passado por parametro
- **indexOf** verifica qual é o index do item que foi passado por parâmetro (Quando não existir ele retorna -1)
- **remove** que remove o item que passar por parâmetro
- **removeAt** que remove o item no index que passar por parâmetro
- **shuffle** que embaralha a lista
- **clear** limpa a lista
    
    
    ## Interação da Lista
    
    O Dart permite pegar uma lista com um começo e/ou fim e já atribuir para uma lista derivada, com a função **sublist**. como no exemplo 
    
    ![Untitled](Listas%20bc26ba9cbf454a14a1b8966c00d0cf09/Untitled%202.png)
    
    Existe também como passar uma função como parâmetro em um função da lista, o **forEach** executa a função passada pra cada item da lista como por exemplo 
    
    ![Untitled](Listas%20bc26ba9cbf454a14a1b8966c00d0cf09/Untitled%203.png)
    
    ## Outras funções das Listas
    
    Existes construtores de listas que podem facilitar o preenchimento da lista como o construtor **List.filled** que constrói uma lista com a quantidade de itens que especificar e com o item que especificar por exemplo:
    
    ![Untitled](Listas%20bc26ba9cbf454a14a1b8966c00d0cf09/Untitled%204.png)
    
    Também existe o construtor que gera uma lista com a quantidade que passar por parâmetro mas de acordo com a função passada como parâmetro que é o List.generate, segue o exemplo: 
    
    ![Untitled](Listas%20bc26ba9cbf454a14a1b8966c00d0cf09/Untitled%205.png)
    
    Sambem é utilizável a função anônima 
    
    ![Untitled](Listas%20bc26ba9cbf454a14a1b8966c00d0cf09/Untitled%206.png)
    
    Funções isEmpty e isNotEmpty que são funções que retornam se a função é vazia ou não vazia respectivamente, segue exemplo
    
    ![Untitled](Listas%20bc26ba9cbf454a14a1b8966c00d0cf09/Untitled%207.png)