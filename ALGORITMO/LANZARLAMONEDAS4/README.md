# core.lucia
## ALGORITMO DE SEMANA 4 DE LANZAR LA MONEDA.
## INSTRUCCIONES:
* A partir de los datos que recibimos primero un nombre y un valor, luego otro nombre y otro valor, utilizando la función integrada aleatoria() simulamos el lanzamiento de una moneda. 
Debemos devolver el nombre del ganador en mayúsculas y el valor que gana.
Para evitar el fraude, si un jugador pone un valor de cero o negativo, el ganará automáticamente. En caso de que ambos hagan trampa, se devuelve "juego cancelado".
``` psc Algoritmo lanzarLaMoneda
	Escribir "Ingrese el nombre del primer jugador:"
	Leer jugador1
	Escribir "Ingrese la cantidad a jugar:"
	Leer cantidad1
	Escribir "Ingrese el nombre del segundo jugador:"
	Leer jugador2
	Escribir "Ingrese la cantidad a jugar:"
	Leer cantidad2
	
	Si cantidad1 <= 0 | cantidad2 <= 0 Entonces
		Si cantidad1 <= 0 & cantidad2 <=	0 Entonces
			Imprimir "Juego cancelado"
	SiNo
		Si cantidad1 <= 0 Entonces
			Imprimir "El ganador del juego es:", Mayusculas(jugador2), "cantidad ganada: 0"
		SiNo
			Imprimir "El ganador del juego es:", Mayusculas(jugador1), "cantidad ganada: 0"
		FinSi
	FinSi
SiNo
	Si Aleatorio(1,2) = 1 Entonces
		Imprimir "El ganador del juego: ", Mayusculas(jugador1), "cantidad ganada: ", cantidad2
	SiNo
		Imprimir "El ganador del juego: ", Mayusculas(jugador2), "cantidad ganada: ", cantidad1
		
	FinSi
	
FinSi

FinAlgoritmo
* Agregue una imagen con mi resultado.
![image](https://github.com/luciaflortop/core.lucia/assets/132409270/ba964ff8-366d-4916-9855-5ca3743fbc89)
*  ALETA.
FIN DE MI ALGORITMO DE SEMANA 4 DE LANZAR LA MONEDA.


