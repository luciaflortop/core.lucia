# core.lucia
## ALGORITMO DE SEMANA 5 DE PUNTO CENTRAL.
## INSTRUCCIONES:
* Escribe una función llamada midpoint que dado 2 valores (pueden ser negativos) no devuelva el valor del punto central entre ellos.

```psc Funcion resultado<-puntoCentral(num1,num2)
	Si num1 > 0 Entonces
		Si num2 > 0 Entonces
			Si num1 > num2 Entonces
				resultado = num2 + ((num1 - num2)/2);
			SiNo
				resultado = num1 + ((num2 - num1)/2);
				FinSi
		SiNo
			resultado = num1- ((num1 + abs(num2))/2);
			FinSi
		SiNo
		Si num2 > 0 Entonces
			resultado = num1 + ((num1 + abs(num2))/2);	
		SiNo
			Si abs(num1) > abs(num2)Entonces
				resultado = num1 + ((abs(num1) - abs(num2))/2);
			SiNo
				resultado = num2 + ((abs(num2) - abs(num1))/2);
			FinSi
		FinSi
	FinSi
FinFuncion

Algoritmo ejemploPuntoCentral
	Imprimir puntoCentral(40,80)
	Imprimir puntoCentral(50,50)
	Imprimir puntoCentral(-50,50)
	Imprimir puntoCentral(40,-40)
	FinAlgoritmo

* ALETA.
* FIN DE MI ALGORITMO DE SEMANA 5 DE PUNTO CENTRAL.
