# core.lucia
##  ALGORITMO DE PAR O IMPAR DE SEMANA #4
## INSTRUCCIONES:
* Solicita un número del 1 al 50.Si el número no está entre esos valores, reporta el error y solicitálo de nuevo hasta que obtengas un número válido. Luego muestra en la pantalla todos los números del 1 hasta ese número.
*  Luego muestra en la pantalla todos los números del 1 hasta ese número.
*  ``` PSC Algoritmo parOImpar
	Repetir
		Escribir "Ingrese un numero entre el 1 y 50:"
		Leer num 
		Si num  < 1 | num > 50 Entonces
			Imprimir "Numero invalido"
		FinSi
	Mientras Que num < 1 | num > 50
	
	par = num % 2 = 0 
	
	Para contador = 1 Hasta num Con Paso 1 Hacer
		Si contador % 2 = 0 & par Entonces
		Imprimir contador	
		FinSi
		Si contador % 2 = 1 & ~(par) Entonces
			Imprimir contador
		FinSi
	FinPara
	
FinAlgoritmo
* agrego una imagenm para que se pueda ver mi resultado:
*  ![image](https://github.com/luciaflortop/core.lucia/assets/132409270/25933242-4a78-4e09-a711-45be344a51b2)
 
