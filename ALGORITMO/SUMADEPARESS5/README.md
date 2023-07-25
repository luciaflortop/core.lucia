# core.lucia
## ALGORITMO DE SEMANA 5 SUMA DE PARES.
## INSTRUCCIONES:
* Escribe una función llamada sumOfPairs que solicita un número del 1 al 100 indefinidamente, si se ingresa un número negativo o mayor a 100,
 se detiene la solicitud de más números y devuelve la suma de todos los números pares ingresados.


```psc Funcion resultado<-sumaDePares ()
	Definir resultado Como Real
	Definir suma Como Real
	suma = 0;
	Repetir
		Escribir "Escribir un numero entre el 1 y 100:";
		Leer num;
		Si num < 1 | num > 100 Entonces
			Imprimir "Numero invalido"
		SiNo
			Si num % 2 = 0 Entonces
				suma = suma + num;
			FinSi
		FinSi
	Mientras Que num >=1 & num <=100
	resultado = suma;
FinFuncion

Algoritmo ejemploSumaDePares
	Imprimir sumaDePares() 
FinAlgoritmo

* imagen con mi resultado.
![image](https://github.com/luciaflortop/core.lucia/assets/132409270/082923a2-45cc-4f11-80bd-edb5763b4feb)

* ALETA.
* FIN DE MI ALGORITMO DE SEMANA 5 DE SUMA DE PARES.
