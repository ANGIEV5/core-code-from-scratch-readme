Algoritmo Fullname04
		imprimir "Ingrese su nombre"
		leer name
		imprimir "Ingrese su apellido"
		leer lastname
		primeraLetra = Mayusculas(Subcadena(name ,0,0)) 
		restodelnombre = Subcadena(name,1, Longitud(name) -1)
		escribir primeraLetra + restodelnombre 
		lastNamePrimeraletra = Mayusculas(subcadena(lastname ,0 ,0))
		restoLastName = Subcadena(lastname, 1, Longitud(lastname) -1)
		Escribir lastNamePrimeraletra + restoLastName
FinAlgoritmo


