Funcion result <- timeConverted ( number )
	definir result Como Caracter
	Definir dias, horas, minutos, seconds Como Entero;
	seconds = number % 60;
	minutos = trunc(number/60) % 60;
	horas = trunc(number/3600) % 24;
	dias = trunc(number/86400);
	result= Concatenar("dias: ", ConvertirATexto(dias));
	result= Concatenar(result,",horas: ");
	result = Concatenar(result, ConvertirATexto(horas));
	result = Concatenar(result, "minutos:");
	result = Concatenar(result, ConvertirATexto(minutos));
	result = Concatenar(result,"segundos:");
	result = Concatenar(result, ConvertirATexto(seconds));
Fin Funcion
	
Algoritmo time
	imprimir timeConverted(1000000)
FinAlgoritmo
