# Dicas-de-Python---Avançado

•	COMPREENSÃO DE LISTA
	Além das operações de sequencia e métodos de lista, o python inclui uma operação mais avançada chamada de compreensão de listas.
	As compreensões de listas nos permitem construir listas usando uma notação diferente. Você pode pensar nisso essencialmente como um loop construído dentro de colchetes. Um exemplo simples:
# pega todas as letras em uma string
Lst = [x for x in ‘word’]
# checar
Lst
Esta é a idéia básica de uma compreensão de lista.
	Vejamos mais alguns exemplos de compreensões de lista em python:
#eleva ao quadrado os itens no range e o transformam em lista
Lst = [x==2 for x in range(0,11)]
# checar
Lst

Vamos ver como adicionar condições usando o if.
# criar uma lista de números pares, utilizando para isso o if
Lst = [x for x in range(11) if x % 2 ==0]
# checar
Lst
	Também podemos fazer operações aritméticas mais complicadas:
# converter celsius para fahrenheit
Celsius = [0,10,20.1,34.5]
Fahrenheit = [((9/5)*temp+32) for temp in Celsius]
fahrenheit

	também podemos realizar compreensões de lista aninhadas, por exemplo:
lst = [x**2 for x in [x**2 for x in range(11)]]
lst
	Após esta seção, você deve se sentir confortável em ler e escrever compreensões de listas.

Exercícios
1 – usando compreensão de listas, crie uma lista com os números pares de 0 a 30.

2 – crie uma função que receba uma string e retome uma lista com apenas as vogais
# exemplo vogais(‘abcde’)
 
