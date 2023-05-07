Funcion resultado <- TotalPrice (price, vat )
	resultado = price + (price * (vat/100) ) 
	Si resultado > 3000 Entonces
		resultado = resultado - (resultado * 0.1) 
	Fin Si
FinFuncion

Algoritmo Totalprice2
	Imprimir TotalPrice(5000,21)
	
FinAlgoritmo


nota: resulto con ayuda del profesor
