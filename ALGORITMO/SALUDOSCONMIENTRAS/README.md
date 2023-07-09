# core.lucia
## ALGORITMO DE SALUDOS CON MIENTRAS.
## INSTRUCCIONES:
* Para este desafío, necesita crear un programa que imprima un saludo basado en una hora ingresada.
* ``` psc Algoritmo saludos
	Imprimir "====Saludos===="
	Definir contador Como Entero
	Definir continuar Como Caracter
	contador <- 0
	continuar <- "Si"
	Mientras continuar = "Si" Hacer
		contador <- contador + 1
		Imprimir "Ingrese la hora actual(0-24):"
	Leer hora
	Si hora <= 10 Entonces
		Imprimir "Buenos dias!"
	SiNo
		Si hora <= 16 Entonces
			Imprimir "Buenas tardes!"
		SiNo
			Imprimir "Buenas noches!"
		FinSi
	Fin si 
	
	Imprimir "Desea continuar? Si/No"
	Leer continuar
FinMientras

Imprimir "Cantidad de saludos: " + ConvertirATexto(contador)
FinAlgoritmo
* ALETA.
* FIN DE MI ALGORITMO DE SALUDOS CON MIENTRAS.
