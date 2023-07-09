# core.lucia
## ALGORITMO DE PROMEDIO DE VENTAS Y COMISION.
## INSTRUCCIONES:
* Crea un programa que pregunte las ventas que ha tenido el vendedor.
* ``` psc Algoritmo promedioDeventasYComision
	Escribir "Ingresar el numero total de ventas"
	Leer NumeroTotalDeVentas
	ingresoTotal=0 
	Para venta=1 Hasta NumeroTotalDeVentas Con Paso 1 Hacer
		Escribir "Ingrese el numero de valor de la venta ",venta," :"
		Leer cantidaDeventas
		ingresoTotal = ingresoTotal + cantidaDeventas
	FinPara
	
	promedio = ingresoTotal / cantidaDeventas
	Escribir "El promedio de ventas es: ", promedio
	
	Si cantidaDeventas < 5 Entonces
		Escribir "La comision recibida por las ventas es:", ingresoTotal * 0.15 = ingresoTotal /100*15
	SiNo
		Escribir "La comision recibida por el ventas es:", ingresoTotal * 0.10 = ingresoTotal /100*10
	FinSi
FinAlgoritmo
* Agregue una imagen para que miren mi resultado.
* ![image](https://github.com/luciaflortop/core.lucia/assets/132409270/8f269710-249d-40f2-ab04-1cd4c18ca278)

* ALETA.
* FIN DE MI ALGORITMO DE PROMEDIO DE VENTAS Y COMISION.
