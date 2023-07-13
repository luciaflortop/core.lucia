# core.lucia
## ALGORITMO DE SEMANA 4 DE LANZAR DADOS.
## INSTRUCCIONES:
Haz un programa que simule el lanzamiento de 2 dados 10 veces, y muestre para cada lanzamiento los valores de los dos dados separados por un espacio.
En caso de que los dos dados arrojen el mismo valor, además del resultado, agrega una cadena al final que diga "los dados son iguales".
* ``` pcs Algoritmo lanzarDados
	Definir dado1, dado2 Como Entero
	Para contar=1 Hasta 10 Con Paso 1 Hacer
		dado1 = Aleatorio(1,6)
		dado2 = Aleatorio(1,6)
		Si dado1 = dado2 Entonces
			Imprimir dado1, " ", dado2, "Los dados son iguales"
		SiNo
			Imprimir dado1, " ", dado2
		FinSi
	FinPara
FinAlgoritmo
* Agrego una imagen para que se vea mi resultado.
* ![image](https://github.com/luciaflortop/core.lucia/assets/132409270/dbc5e780-c653-4315-bbf0-a574b4a1d726)
* ALETA.
* FIN DE MI ALGORITMO DE LANZAR LOS DADOS DE SEMANA 4.
