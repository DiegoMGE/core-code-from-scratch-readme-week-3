# Diego Orellana - CoreCode Bootcamp 🚀
## Week 3
### Monday Challenges
## Simple Calculator
```python
Algoritmo simpleCalculator
	Imprimir '======= Simple Calculator ======='
	Imprimir 'Ingrese el primer número'
	Leer n1
	Imprimir "Ingrese el segundo número'
	Leer n2
	Imprimir 'Ingrese el tipo operación: +, -, *, /'
	Leer operation
	
	Si operation == '+' Entonces
		Imprimir 'Procesando: ' n1 ' ' operation ' ' n2
		Imprimir 'Resultado: ' ConvertirATexto(n1+n2)
	FinSi
	Si operation == '-' Entonces
		Imprimir 'Procesando: ' n1 ' ' operation ' ' n2
		Imprimir 'Resultado: ' ConvertirATexto(n1-n2)
	FinSi
	Si operation == '*' Entonces
		Imprimir 'Procesando: ' n1 ' ' operation ' ' n2
		Imprimir 'Resultado: ' ConvertirATexto(n1*n2)
	FinSi
	Si operation == '/' Entonces
		Imprimir 'Procesando: ' n1 ' ' operation ' ' n2
		Si n2 == 0 Entonces 
			Imprimir 'Indefinido matemáticamente'
		FinSi
		Imprimir 'Resultado: ' ConvertirATexto(n1/n2)
	FinSi
	
FinAlgoritmo
```

## Special number

### Tuesday Challenges
## Simple calculator with Switch
```python
Algoritmo simpleCalculator
	Imprimir '======= Simple Calculator ======='
	Imprimir 'Ingrese el primer número'
	Leer n1
	Imprimir "Ingrese el segundo número'
	Leer n2
	Imprimir 'Ingrese el tipo operación: +, -, *, /'
	Leer operation
	
	Segun operation Hacer
		'+':
			Imprimir "Procesando: " n1 operation n2
			Imprimir "Resultado: " ConvertirATexto(n1+n2) 
		'-':
			Imprimir "Procesando: " n1 operation n2
			Imprimir "Resultado: " ConvertirATexto(n1-n2)
		'*':
			Imprimir "Procesando: " n1 operation n2
			Imprimir "Resultado: " ConvertirATexto(n1*n2)
		'/':
			Imprimir "Procesando: " n1 operation n2
			Si n2 == 0 Entonces 
				Imprimir "Indefinido"
			FinSi
			Imprimir "Resultado: " ConvertirATexto(n1/n2)
		De Otro Modo:
			Imprimir 'Operación inválida'
	FinSegun
	
FinAlgoritmo
```

## Multi Option Program


### Wednesday Challenges


### Thursday Challenges

.
