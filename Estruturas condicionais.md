Estruturas condicionais são blocos de código em programação que permitem que um programa execute diferentes ações com base em uma condição específica. Em Python, a estrutura condicional mais comum é a instrução `if`, que permite que você execute um bloco de código se uma condição for verdadeira. Além disso, você pode usar instruções `elif` e `else` para lidar com múltiplas condições.

Aqui está a sintaxe básica de uma estrutura condicional em Python:

```python
if condição:
    # Código a ser executado se a condição for verdadeira
elif outra_condição:
    # Código a ser executado se a condição for falsa, mas outra_condição for verdadeira
else:
    # Código a ser executado se nenhuma das condições anteriores for verdadeira
```

Aqui estão alguns exemplos de estruturas condicionais:

```python
idade = 18

if idade < 18:
    print("Você é menor de idade.")
elif idade == 18:
    print("Você tem exatamente 18 anos.")
else:
    print("Você é maior de idade.")

# Saída: "Você tem exatamente 18 anos."
```

Neste exemplo, o programa verifica a idade da pessoa e imprime uma mensagem com base na condição. Se a idade for menor que 18, imprime "Você é menor de idade". Se a idade for igual a 18, imprime "Você tem exatamente 18 anos". Caso contrário, se nenhuma das condições anteriores for atendida, imprime "Você é maior de idade".

As estruturas condicionais são fundamentais para controlar o fluxo de um programa e tomar decisões com base em diferentes situações. Elas permitem que você escreva código que seja flexível e reaja a diferentes cenários.
