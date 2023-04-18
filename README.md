Algoritmo OpcionMultiple
	imprimir " Opción Multiple "  
	Imprimir " 1. Suma de dos números"
	Imprimir " 2. Día de la semana"
	Imprimir " 3. Calcular longitud de un texto"
	Imprimir "Ingrese una opción"
	leer opcion 
	Segun opcion Hacer
		1:
			Imprimir " 1.Suma de dos números"
			Imprimir "Ingrese un número"
			leer num1 
			Imprimir "Ingrese un número"
			leer num2 
			resultado = num1 + num2
			Imprimir resultado 
		2:
			Imprimir " 2.Día de la semana "
			imprimir "Ingrese un número (1-7) "
			leer dia
			Segun dia Hacer
		        1:
					Imprimir "Lunes"
				2:
					Imprimir "Martes"
				3:
					Imprimir "Miercoles"
				4: 
					Imprimir "Jueves"
				5: 
					Imprimir "Viernes"
				6: 
					Imprimir "Sabado" 
				7: 
					imprimir "Domingo"
				De Otro Modo:
					Imprimir "Número no es valido / Ese día de la semana no existe"
			Fin Segun
		3:
			Imprimir " 3. Calcular longitud de un texto" 
			Imprimir " Ingrese un texto"
			leer texto
			imprimir "resultado:" = ConvertirATexto(Longitud(texto))
		De Otro Modo:
			imprimir " Opcion es incorrecta"
	Fin Segun
FinAlgoritmo

