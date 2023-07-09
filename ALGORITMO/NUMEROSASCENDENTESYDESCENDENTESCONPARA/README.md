# core.lucia
## ALGORITMO DE NUMEROS ASCENDENTES Y DESCENDENTES CON PARA.
## INSTRUCCIONES:
*  Para este desafío vamos a imprimir números en orden ascendente o descendente.
*   El usuario debe ingresar un número, y luego debe ingresar si desea imprimir los números en orden ascendente o descendente.
*   ``` psc Algoritmo numerosAscendentesODescendentesConPara
	Imprimir "==== Numeros ascendentes y descendentes===="
	Imprimir "Ingrese un numero:"
	Leer numero
	Imprimir "Opcion 1. Imprimir numeros ascendentes"
	Imprimir "Opcion 2. Imprimir numeros descendentes"
	Imprimir "Ingrese la opcion:"
	Leer op
	Segun op Hacer
		1:
			Imprimir "@ Numeros ascendentes @"
			Para i <- 1 Hasta numero Con Paso 1 Hacer
				Imprimir ConvertirATexto(i)
			Fin Para
		2:
			Imprimir "@ Numeros descendentes @"
			Para i <- numero Hasta 1 Con Paso -1 Hacer
				Imprimir ConvertirATexto(i)
			FinPara
	    De Otro Modo:
			Imprimir "La opcion es incorrecta!"
	FinSegun
FinAlgoritmo
* Agregue una imagen para que se vea mi resultado.
* ![image](https://github.com/luciaflortop/core.lucia/assets/132409270/69cf1540-17d5-45c9-bfea-89986df18096)
*  ALETA.
*  FIN DE MI ALGORITMO DE NUMEROS ASCENDETES Y DESCENDENTES CON BUCLE PARA.
