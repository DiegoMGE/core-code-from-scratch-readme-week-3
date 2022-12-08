# Diego Orellana - CoreCode Bootcamp 🚀
## Week 3
## Monday Challenges
- [simple calculator](https://github.com/DiegoMGE/core-code-from-scratch-readme-week-3/blob/main/README.md#simple-calculator)
- [special number](https://github.com/DiegoMGE/core-code-from-scratch-readme-week-3/blob/main/README.md#special-number)

### Simple Calculator
```python
Algoritmo simpleCalculator
	Imprimir '======= Simple Calculator ======='
	Imprimir 'Ingrese el primer número'
	Leer n1
	Imprimir 'Ingrese el segundo número'
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
		Si n2 == 0 Entonces 
			Imprimir 'Procesando: ' n1 ' ' operation ' ' n2
			Imprimir 'Indefinido matemáticamente'
		SiNo
			Imprimir 'Procesando: ' n1 ' ' operation ' ' n2
			Imprimir 'Resultado: ' ConvertirATexto(n1/n2)
		FinSi
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
- [Simple Calculator with Switch](https://github.com/DiegoMGE/core-code-from-scratch-readme-week-3/blob/main/README.md#simple-calculator-with-switch)
- [Multi Option Program](https://github.com/DiegoMGE/core-code-from-scratch-readme-week-3/blob/main/README.md#multi-option-program)

### Simple calculator with Switch
```python
Algoritmo simpleCalculator
	Imprimir '======= Simple Calculator ======='
	Imprimir 'Ingrese el primer número'
	Leer n1
	Imprimir "Ingrese el segundo número'
	Leer n2
	Imprimir 'Ingrese la operación: +, -, *, /'
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
			Si n2 == 0 Entonces 
				Imprimir "Procesando: " n1 operation n2
				Imprimir "Indefinido"
			SiNo
				Imprimir "Procesando: " n1 operation n2
				Imprimir "Resultado: " ConvertirATexto(n1/n2)
			FinSi
		De Otro Modo:
			Imprimir 'Operación inválida'
	FinSegun
	
FinAlgoritmo
```

### Multi Option Program
```python
Algoritmo multiOption
	Imprimir '======= Multi Opción ======='
	Imprimir 'Opciones Disponibles'
	Imprimir '1. Suma de dos números'
	Imprimir '2. Imprimir día de la semana'
	Imprimir '3. Calcular longitud de texto'
	Leer usuario
	
	Segun usuario Hacer 
		1:
			Imprimir 'El usuario escogió la opción ' usuario
			Imprimir 'Ingresar el primer número'
			Leer numero1
			Imprimir 'Ingresar el segundo número'
			Leer numero2
			Imprimir 'Resultado: ' (numero1 + numero2)
		2:
			Imprimir 'El usuario escogió la opción ' usuario
			Imprimir 'Ingrese el día de la semana en números (1-7)'
			Imprimir 'Ejemplo: 1. Lunes'
			Leer diaSemana
			
			Segun diaSemana Hacer
				1:
					Imprimir 'Lunes'
				2:
					Imprimir 'Martes'
				3:
					Imprimir 'Miércoles'
				4:
					Imprimir 'Jueves'
				5:
					Imprimir 'Viernes'
				6:
					Imprimir 'Sábado'
				7:
					Imprimir 'Domingo'
				De Otro Modo:
					Imprimir 'Número inválido'
			FinSegun
		3:
			Imprimir 'El usuario escogió la opción ' usuario
			Imprimir 'Ingrese el texto para calcular su longitud, el espacio también se cuenta.'
			Leer textoUsuario
			Imprimir 'La longitud del texto ingresado es de ' Longitud(textoUsuario)
		De Otro Modo:
			Imprimir 'La opción ingresada no es válida.'
	FinSegun
	
FinAlgoritmo
```

## Wednesday Challenges
- [Multiplication Tables](https://github.com/DiegoMGE/core-code-from-scratch-readme-week-3/blob/main/README.md#multiplication-tables)
- [Simple Calculator with Do While](https://github.com/DiegoMGE/core-code-from-scratch-readme-week-3/blob/main/README.md#simple-calculator-with-do-while)

### Multiplication Tables
```python
Algoritmo multiplicationTables
	start <- 1
	end <- 10
	
	Imprimir '======= Multiplication Tables ======='
	Imprimir 'Ingrese la tabla a calcular:'
	Leer tabla
	Imprimir 'Tabla de ' tabla
	
	Mientras start <= end Hacer
		Imprimir tabla ' * ' start ' = ' (tabla*start)
		start <- start + 1
	FinMientras
	
FinAlgoritmo
```

### Simple Calculator with Do While
```python
Algoritmo simpleCalculatorDoWhile
	Imprimir '======= Simple Calculator ======='
	Repetir 
		Imprimir 'Ingrese el primer número'
		Leer n1
		Imprimir "Ingrese el segundo número'
		Leer n2
		Imprimir 'Ingrese la operación: +, -, *, /'
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
			Si n2 == 0 Entonces 
				Imprimir 'Procesando: ' n1 ' ' operation ' ' n2
				Imprimir 'Indefinido matemáticamente'
			SiNo
				Imprimir 'Procesando: ' n1 ' ' operation ' ' n2
				Imprimir 'Resultado: ' ConvertirATexto(n1/n2)
			FinSi
		FinSi
		
		Imprimir 'Deseas continuar con otra operación? Si / No'
		Leer continue
	Hasta Que continue == 'No' | continue == 'no'
FinAlgoritmo
```

## Thursday Challenges
- [Multiplication Tables with For]()
- [Ascending and Descending Numbers]()
- [Greetings]()

.
