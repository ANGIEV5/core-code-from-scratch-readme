Algoritmo Sales04
	escribir "Escriba la cantidad de ventas" 
	leer CantidadDeVentas
	Escribir "totalDeVentas: " + ConvertirATexto(CantidadDeVentas)
	Para contador<- 1 Hasta CantidadDeVentas Con Paso 1 Hacer
		Escribir "ingresa la venta numero" + ConvertirATexto(contador) + ":" 
		leer valorDeVenta 
		totalDeVentas = totalDeVentas + valorDeVenta
	Fin Para
	promedio = totalDeVentas + CantidadDeVentas
	Si CantidadDeVentas >= 5  Entonces
		comision = totalDeVentas * 0.15 
	SiNo
		comision = totalDeVentas * 0.1
	Fin Si
	Escribir comision
FinAlgoritmo

nota: El código no funciona pero no se por que. 
