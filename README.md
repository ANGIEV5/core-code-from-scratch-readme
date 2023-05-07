Funcion resultado <- sumofpairs (1, 100)
	definir resultado Como Real
	suma = 0
	
	Repetir
		Escribir "Ingrese un número del 1 al 100"
		leer num 
		Si num <= 1 | num >= 100 Entonces
			Escribir "operación invalida" 
		
			Si num % 2 = 0 Entonces
				suma = suma + num 
			Fin Si
		Fin Si
	Mientras Que num <= 1 | num >= 1 
	resultado = suma
Fin Funcion

Algoritmo sumaPares
	Imprimir sumofpairs(1,100)
FinAlgoritmo

Nota: No sale la suma al final y no entiendo por que.
