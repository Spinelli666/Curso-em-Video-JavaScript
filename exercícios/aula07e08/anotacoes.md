# Operadores

## Operadores aritméticos

Os operadores são: +, -, *, /, %, ** 

** -> Esse operador é a potência <br>
% -> Resto da divisão 

## Operadores de atribuição

### Atribuções Simples

Sempre que colocar uma variavel para uma conta só colocar: Exemplo: "var a = 5 + 3"

### Auto-atribuições

var n = 3
n= n + 4

A variável **n** está valendo 3, na próxima linha como eu coloquei **n** na frente, vai ocorrer que irá somar o que está depois, no caso "n + 4", então no final dará 7, pois 4 + 3 é 7

### Simplificado

+= <br>
-= <br>
*= <br>
/= <br>
%= <br>
**=

### Incremento

++ <br>
*--*

## Operadores Relacionais

Os operadores são: >, <, >=, <=, ==, !=

### Identidade

5 == 5 -> true <br>
5 == '5' -> true

5 === '5' -> false (Não tem o mesmo tipo)

## Operadores Lógicos

Os operadores são: !, &&, ||

! -> Negação <br>
&& -> Conjunção <br>
|| -> Disjunção

#### Negação

true -> false <br>
false -> true

#### Conjunção

true && true -> true <br>
true && false -> false <br>
false && true -> false <br>
false && false -> false

#### Disjunção

true || true -> true <br>
true || false -> true <br>
false || true -> true <br>
false || false -> false

## Operadores Ternário

Os operadores são: ?, :

teste "?" true ":" false

Exemplo: média >= 7.0 ? "Aprovado" : "Reprovado"