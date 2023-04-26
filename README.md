algoritmo FullName04
	imprimir "Ingrese su nombre"
	leer name
	imprimir "Ingrese su apellido"
	leer lastname
	escribir mayusculas(name) 
	escribir mayusculas(lastname) 
	name1= Mayusculas(Subcadena(name,0,0)) + Minusculas(Subcadena(name,1,Longitud(name)-1)) 
	lastname1 = Mayusculas(Subcadena(lastname,0,0)) + Minusculas(Subcadena(lastname,1,Longitud(lastname)-1))
	Imprimir name1, " ",lastname1
FinAlgoritmo  

