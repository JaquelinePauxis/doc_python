Em Python, a classe de retorno (ou tipo de dado de retorno) de uma função não é especificamente declarada como parte da função.
O tipo de dado retornado é determinado implicitamente com base no valor que a função retorna. Python é uma linguagem de tipagem dinâmica,
o que significa que o tipo de dado de uma variável é determinado em tempo de execução.

No entanto, você pode especificar o tipo de retorno de uma função usando anotações de tipo (Type Hints)a partir do Python 3.
As anotações de tipo são uma forma de documentar o tipo esperado de um valor de retorno de uma função.
Isso pode ser útil para a legibilidade do código e para ferramentas que fazem análise estática de código.

Aqui está um exemplo de como usar anotações de tipo para especificar o tipo de retorno de uma função:

def soma(a: int, b: int) -> int:
    resultado = a + b
    return resultado

resultado_da_soma = soma(5, 3)
# 'resultado_da_soma' é do tipo 'int' de acordo com a anotação de tipo da função 'soma'

 Neste exemplo, a função soma tem anotações de tipo que indicam que ela aceita dois 
 argumentos inteiros (a e b) e retorna um valor inteiro (int). No entanto, observe que 
  essas anotações de tipo são usadas principalmente para fins de documentação e análise 
  estática de código; elas não afetam o comportamento em tempo de execução da função. 
Python ainda é uma linguagem de tipagem dinâmica, e você pode retornar qualquer tipo de
dado válido, independentemente das anotações de tipo. As anotações de tipo são uma prática recomendada, mas são opcionais.


  
