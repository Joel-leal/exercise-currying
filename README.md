## Currying

## Exercício 1: Configurar mensagens
Crie uma função curried que receba:
1. Um prefixo.
2. Um sufixo.
3. Uma mensagem.

A função deve retornar a mensagem formatada no estilo: `<prefixo> mensagem <sufixo>`.

---

## Exercício 2: Calcular média ponderada
Implemente uma função curried que receba:
1. Uma lista de pesos.
2. Uma lista de valores.

A função deve calcular e retornar a média ponderada dos valores com base nos pesos fornecidos.


---

## Composição de Funções f(g(x))

## Exercício 3: Compor funções de transformação de strings
Implemente uma função `compose` que permita compor duas ou mais funções. Use-a para criar uma nova função que:
1. Converta uma string para maiúsculas.
2. Remova espaços extras no início e no final da string.
3. Adicione um ponto final ao final da string.

Teste o resultado com uma entrada, como `"  olá mundo  "`.

---

## Exercício 4: Compor funções de transformação de números
Implemente uma função `compose` que permita compor duas ou mais funções. Use-a para criar uma nova função que:
1. Multiplique um número por 2.
2. Subtraia 3 do resultado.
3. Eleve o resultado ao quadrado.

Teste o resultado com um número, como `5`.
