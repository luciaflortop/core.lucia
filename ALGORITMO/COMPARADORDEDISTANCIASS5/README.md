# core.lucia
## ALGORITMO DE SEMANA 5 DE COMPARADOR DE DISTANCIAS.
## INSTRUCCIONES:
Crea una función llamada compareDistances que solicite 5 números, estos pueden ser positivos o negativos, suma los positivos con los positivos y los negativos con los negativos,
la función debería devolver verdadero si hay más distancia a 0 con los números positivos o falsos si la distancia es mayor con los negativos.

4, 12 , 100, 8, -60 --> verdadero

40, 120 , 10, -80, -91 --> Falso


``` psc
Funcion resultado<-compararDistancias()
	Definir resultado Como Logico;
	Definir numeronegativo Como Real;
	Definir numeropositivo Como Real;
	numeronegativo = 0;
	numeropositivo = 0;
	Para contar=1 Hasta 5 Con Paso 1 Hacer
		Escribir "Escribir un numero:"
		Leer num
		Si num > 0 Entonces
			numeropositivo = numeropositivo + num;
		SiNo
			numeronegativo = numeronegativo + num;
			FinSi
		FinPara
	resultado = numeropositivo >  abs(numeronegativo);
FinFuncion

Algoritmo ejemploCompararDistancias
	Imprimir compararDistancias()
FinAlgoritmo


* ALETA.
* FIN DE MI ALGORITMO DE SEMANA 5 COMPARADOR DE DISTANCIAS.

