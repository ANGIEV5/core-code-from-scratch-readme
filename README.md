Algoritmo Lejano04
	numeroMaslejano = 0 
	Para i<-1 Hasta 5 Con Paso 1 Hacer
		escribir "Ingrese número" + ConvertirATexto(i) + ":"
		leer num
		Si abs(num) > abs(numeroMaslejano) Entonces
			numeroMaslejano = num
		Fin Si
	Fin Para
	escribir numeroMaslejano
	
FinAlgoritmo


nota: Realizado con ayuda del profesor
