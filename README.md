lgoritmo Tosscoin
	Escribir "Ingrese un nombre"
	leer nombre1
	Escribir "Ingrese un número"
	leer num1
	Escribir "Ingrese un nombre"
	leer nombre2
	Escribir "Ingrese un número"
	leer num2
	Si num1 <= 0 | num2 <= 0  Entonces
		Si  num1<= 0 &	num2 <= 0 Entonces
			Escribir "Juego cancelado"
		Fin Si
	
	SiNo
		Si num1 <= 0 Entonces
			Escribir "Ganador: " nombre2 
		SiNo
			Escribir "Ganador: " nombre1 
		Fin Si
	Fin Si
	Si Aleatorio(num1,num2)= num1 Entonces
		Escribir "Ganador: " Mayusculas(nombre1) 
	SiNo
		escribir "ganador: " Mayusculas(nombre2)
	Fin Si
FinAlgoritmo
