Algoritmo ProgramaEvenODD
	Imprimir "ingrese un número"
	leer num1
	Imprimir "ingrese segundo número"
	leer num2
	Imprimir "Suma (+) Resta (-) multiplicación (*) división (/) "
	imprimir " ingrese operación con simbolo"
	leer operacion
	Imprimir " procesando"  num1 operacion num2 
	si operacion == "+" Entonces
		resultado = num1 + num2
		fin si
	si operacion == " -" Entonces
			resultado = num1- num2
		FinSi
	si operacion == "*" Entonces
			resultado = num1 * num2
		FinSi
	si operacion == "/" Entonces
		resultado = num1 / num2
	finsi 
	si operacion == "+" | operacion == "-" | operacion == "*" | operacion == "/" Entonces
		Escribir resultado
	SiNo
		escribir "Operación invalidad"
	finsi 
	
FinAlgoritmo
