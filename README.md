Funcion resultado <- reverseDirectionAndSize ( text )
	definir resultado Como Caracter
	resultado = ""
	Para i<- Longitud(text) Hasta  0 Con Paso -1 Hacer
		letter = Subcadena(text,i,i)
		Si letter = Mayusculas(letter) Entonces
			letter = Minusculas(letter)
		SiNo
			letter = Mayusculas(letter)
		Fin Si
		resultado = Concatenar(resultado,letter)
	Fin Para
Fin Funcion
Algoritmo reverse
	Imprimir reverseDirectionAndSize("hola")
FinAlgoritmo


