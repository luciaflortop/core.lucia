# core.lucia
## ALGORITMO DE SEMANA 5 DE CONVERTIDOR DE TIEMPO.
## INSTRUCCIONES:
* Crea una función llamada timeConverter que recibe un número positivo de segundos y devuelve una cadena de texto basada en el número.
* ``` psc Funcion conversorDeTiempo(Segundos)
		Definir Dias, Horas, Minutos, Segs Como Real;  // Corregir el tipo de datos
		
		Dias <- Segundos / 86400  // 1 día tiene 86400 segundos (24 horas * 3600 segundos/hora)
		Segundos <- Segundos % 86400  // Actualizamos la cantidad para quitar los días ya calculados
		
		Horas <- Segundos / 3600  // 1 hora tiene 3600 segundos
		Segundos <- Segundos % 3600  // Actualizamos la cantidad para quitar las horas ya calculadas
		
		Minutos <- Segundos / 60  // 1 minuto tiene 60 segundos
		Segundos <- Segundos % 60  // Los segundos restantes
		
		Escribir "Días: ", Dias, " Horas: ", Horas, " Minutos: ", Minutos, " Segundos: ", Segundos  // Agregar las comas faltantes
FinFuncion

Algoritmo ejemplo_conversorDeTiempo	
	Definir cantidad Como Entero;  // Agregamos el tipo de datos
	
	Escribir "Ingrese una cantidad en segundos: "
	Leer cantidad
	conversorDeTiempo(cantidad)  // Llamamos a la función para obtener el resultado
FinAlgoritmo

* Agrego imgen extra con el resultado.
*  ![image](https://github.com/luciaflortop/core.lucia/assets/132409270/f81908a4-c8d7-4528-ab57-84b60a5aa1d9).
*  ALETA.
*  FIN DE MI ALGORITMO DE SEMANA 5 DE CONVERTIDOR DE TIEMPO.
