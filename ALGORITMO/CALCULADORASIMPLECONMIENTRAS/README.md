# core.lucia 
## ALGORITMO DE CALCULADORA SIMPLE CON SEGUN Y MIENTRAS.
## INSTRUCCIONES:
* Realizar un desafio de hacer una calculadora simple con el paso mientras y que realice operaciones.
* ``` psc Algoritmo calcuSimpleConSegun
	Imprimir "====Calculadora simple===="
	Repetir
	Imprimir "Ingrese primer numero"
	Leer n1
	Imprimir "Ingrese segundo numero"
	Leer n2
	Imprimir "Ingrese una operacion: +,-,*,/"
	Leer op
	si op == "+" | op == "-" | op == "*" | op == "/" Entonces
		Imprimir "Procesando: " + ConvertirATexto(n1) + " " + op + " " + ConvertirATexto(n2)
		Segun op Hacer
			"+": 
				Imprimir "Resultado: " + ConvertirATexto(n1+n2)
			"-": 
				Imprimir "Resultado: " + ConvertirATexto(n1-n2)
			"*":
				Imprimir "Resultado: " + ConvertirATexto(n1*n2)
			"/":
				Imprimir "Resultado: " + ConvertirATexto(n1/n2)
		FinSegun
	SiNo
		Imprimir "?? La operacion no es valida"
	FinSi
	
	Imprimir "Desea continuar? si/No: "
	Leer continuar
    Hasta Que continuar == "no" | continuar == "No" | continuar == "No"
FinAlgoritmo

* ALETA
* FIN DE MI ALGORITMO DE CALCULADORA SIMPLE CON EL PASO SEGUN Y MIENTRAS.
