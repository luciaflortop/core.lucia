# core.lucia   
##  ALGORITMO  DE CALCULADORA SIMPLE CON  INTERRUPTOR: 
##  INSTRUCCIONES O DESCRIPCION :
Para este desafío, realizará una calculadora simple utilizando Switch (Segun) , Esta calculadora puede realizar las siguientes operaciones:

suma (+) 
RESTA(-)
multiplicacion (*) 
division (/)
![image](https://github.com/luciaflortop/core.lucia/assets/132409270/2d0652ee-1331-43cb-89c7-9b921af7702e)
```  psc   Algoritmo CalculadoraSimpleConSegun
		Imprimir "==== Calculadora Simple ===="
		Imprimir "Ingrese primer numero"
		Leer n1
		Imprimir "Ingrese segundo numero"
		Leer n2
		Imprimir "Ingrese una operación: +,-,*,/"
		Leer op
		Si op == "+" | op == "-" | op == "*" | op == "/" Entonces
			Imprimir "Procesando: " + ConvertirATexto(n1) + " " + op + " " + ConvertirATexto(n2)
			Segun op Hacer
				"+":
					Imprimir "Resultado: " + ConvertirATexto(n1 + n2)
				"-":
					Imprimir "Resultado: " + ConvertirATexto(n1 - n2)
				"*":
					Imprimir "Resultado: " + ConvertirATexto(n1 * n2)
				"/":
					Imprimir "Resultado: " + ConvertirATexto(n1 / n2)
			Fin Segun
		SiNo
			Imprimir "?? La operación no es valida"
		FinSi
FinAlgoritmo
