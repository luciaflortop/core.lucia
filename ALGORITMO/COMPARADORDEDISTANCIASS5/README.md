# core.lucia
## ALGORITMO DE SEMANA 5 COMPARADOR DE DISTANCIAS.
## INSTRUCCIONES:
* Crea una función llamada compareDistances que solicite 5 números, estos pueden ser positivos o negativos,
  suma los positivos con los positivos y los negativos con los negativos,
  la función debería devolver verdadero si hay más distancia a 0 con los números positivos o falsos si la distancia es mayor con los negativos.
  

``` psc 
Funcion resultado<-compararDistancias
	Definir resultado Como Logico
	Definir numeroNegativo, numeroPositivo Como Real;
	numeroNegativo = 0;
	numeroPositivo = 0;
	Para contar = 1 Hasta 5 Con Paso 1 Hacer
		Escribir "Escribe un numero"
		Leer num
		Si num >  0 Entonces
			numeroPositivo = numeroPositivo + num;
		SiNo
			numeroNegativo = numeroNegativo + num;
		FinSi
	FinPara
	resultado = numeroPositivo > abs (numeroNegativo)
FinFuncion

Algoritmo ejemplo_ComparadorDeDistacia
	Imprimir compararDistancias()
FinAlgoritmo
* Agrego una imagen para que puedan ver mi resultado.
*   ![image](https://github.com/luciaflortop/core.lucia/assets/132409270/9b34f2ed-c465-41c0-a257-bd65b53acbb3)
*  ALETA.
* FIN DE MI ALGORITMO DE SEMANA 5 DE COMPARADOR DE DISTANCIA.
