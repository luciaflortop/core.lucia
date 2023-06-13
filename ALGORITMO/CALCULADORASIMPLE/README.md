# core.lucia
##  ALGORITMO DE CALCULADORA SIMPLE:
## INSTRUCCIONES  Y DESCRIPCION:
*  Para este desafío, realizará una calculadora simple. Esta calculadora puede realizar las siguientes operaciones:
*  suma (+)
*  resto (-)
*  multiplicacion (*)
*  División (/)
*La calculadora debe pedir al usuario dos números, después de solicitar los dos números, se debe pedir la operación a realizar, ten en cuenta que debe mostrar al usuario las opciones disponibles (+, -, *, /).
*  Lo primero que se debe hacer es validar que la operación que ingresó el usuario sea, si no es una opción válida, se debe mostrar un mensaje de error al usuario, por ejemplo: y terminar el programa ⚠️ La operación no es valida.
Si la operación es válida, se muestra el mensaje: Procesando: <OPERACIÓN A REALIZAR>Por ejemplo, si el usuario ha ingresado los números 10 y 15, así como la operación *, el mensaje debe leer: Procesando: 10 * 15.
Después de este mensaje, se debe mostrar el resultado de la operación. Siguiendo el ejemplo anterior, el resultado de operar 10 * 15 es 150, por lo que el programa debería mostrar:Resultado: 150.
Recuerda usar condiciones para identificar qué debes ejecutar.
*  RESULTADAOS DE  CALCULADORA  SIMPLE  EN  SUMA, RESTA,MULTIPLICACIO Y DIVICION:
```  psc Algoritmo calculadoraSimple 
	Imprimir "Ingrese primer numero"
	Leer n1
	Imprimir "Ingrese segundo numero"
	Leer n2
	Imprimir "Ingrese una operacion:+,-,*,/"
	Leer op
	Si op == "+" | op == "-" | op == "*" | op == "/" Entonces
		Imprimir "Procesando: "+ConvertirATexto(n1) + " " + op + " " + ConvertirATexto(n2)
		Si op == "+" Entonces
			Imprimir "Resultado: " + ConvertirATexto(n1+n2)
		SiNo
		    Si op == "-" Entonces
				Imprimir "Resultado:" + ConvertirATexto(n1-n2)
			SiNo
				Si op == "*" Entonces
					Imprimir "Resultado: " + ConvertirATexto(n1*n2)
				SiNo
					Imprimir "Resultado: " + ConvertirATexto(n1/n2)
				FinSi
			FinSi
		FinSi
	SiNo
		Imprimir "La operacion no es valida"
		
	FinSi
FinAlgoritmo
* ALETA
*  FIN DE MI  ALGORITMO DE CALCADORA SIMPLE.
