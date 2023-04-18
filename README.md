Algoritmo sin_titulo
	Escribir "ingrese el primer numero"
	Leer num1
	
	Escribir "ingrese el segundo numero"
	Leer num2
	
	Escribir "ingrese una operacion valida: +, -, *, /"
	Leer signo

	Segun signo Hacer
		"+":
			resultado = num1 + num2
			Escribir resultado
		"-":
			resultado = num1 - num2
			Escribir resultado
		"*":
			resultado = num1 * num2
			Escribir resultado
		"/":
			resultado = num1 / num2
			Escribir resultado
		De Otro Modo:
			Escribir "la operacion es invalida"
	Fin Segun
FinAlgoritmo
