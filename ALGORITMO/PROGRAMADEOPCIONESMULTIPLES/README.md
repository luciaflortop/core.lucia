# core.lucia 
##   PROGRAMA DE OPCIONES MULTIPLES:
## INSTRUCCIONES O DESCRIPCION:
*  Sumar dos numeros 
*  Imprimir el dia de  la semana  dado el numero de dia .
*  Imprimir la longitud de un  texto dado. 
*  Este programa debe tener un menú de inicio donde el usuario debe seleccionar una de las opciones previamente descritas.
*  Cuando el usuario seleccione cada una de las opciones, el programa realizará lo siguiente:

*  ```  psc  Algoritmo opcionesMultiple
		Imprimir "==== Opcion Multiple ===="
		Imprimir "Opciones Disponibles"
		Imprimir "1. Sumar de dos numeros"
		Imprimir "2. Imprimir dia de la semana"
		Imprimir "3. Calcular longitud de texto"
		Imprimir "Ingrese la opcion:"
		Leer opcion
		Segun opcion Hacer
			1:
				Imprimir 'Opcion 1. Sumar de dos numeros'
				Imprimir 'Ingrese primer numero'
				Leer n1
				Imprimir 'Ingrese segundo numero'
				Leer n2
				Imprimir 'Resultado: ' + ConvertirATexto(n1 + n2)
	
		2:
			Escribir "Escriba dia de la semana"
			Leer dia
			Segun dia Hacer
				1: 
					Mostrar "Lunes"
				2:
					Mostrar "Martes"
				3:  
					Mostrar "Miercoles"
				4:
					Mostrar "jueves"
				5:
					Mostrar "Viernes"
				6: 
					Mostrar "Sabado"
				7: 
					Mostrar "Domingo"
				De Otro Modo:
					Imprimir "Dia incorrecto!"
			FinSegun
		3: 
			Escribir "Ingrese la palabra para calcular la longitud"
			Leer palabra
			Escribir "longitud ", Longitud(palabra)
	FinSegun
FinAlgoritmo
*  ALETA
*  FIN DE MI DESAFIO DE OPCIONES MULTIPLES.
