Algoritmo specialNumber
		Leer n
		Si n == 100 Entonces
			Imprimir 'This is a special number'
		FinSi
	
		Si n % 10 == 0 Entonces
			Imprimir 'This number is multiple of 10'
		FinSi
		si n < 1000 | n % 10 == 0 | n == 100 Entonces
			Imprimir "This number is almost special"
		SiNo
			Imprimir "Just a regular number" 
		FinSi
FinAlgoritmo

