# Diego Orellana - CoreCode Bootcamp 🚀
## Week 3
## Monday Challenges
- [simple calculator]()
- [special number]()

### Simple Calculator
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

### Special number
```python
Algoritmo specialNumber
	Leer n
	Si n == 100 Entonces
		Imprimir 'This is a special number'
	SiNo 
		Si (n < 1000) & (n <> 100) & ((n % 10) == 0) Entonces
			Imprimir 'This number is almost special'
		SiNo
			Imprimir 'Just a regular number!'
		FinSi
	FinSi
FinAlgoritmo
```

## Tuesday Challenges
- [Simple Calculator with Switch]()
- [Multi Option Program]()

### Simple calculator with Switch
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

### Multi Option Program


## Wednesday Challenges
- []()
- []()

## Thursday Challenges
- []()
- []()

.
