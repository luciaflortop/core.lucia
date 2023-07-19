# core.lucia
## ALGORITMO DE SEMANA 4 DE DIRECCION INVERSA Y TAMAÑO.
## INSTRUCCIONES:
Crea una función llamada "ReverseDirectionAndSize" que tome algún texto como parámetro y lo invierta, por ejemplo: "Hola" -> "aloH". 
Además, si las letras son mayúsculas, las convierte en minúsculas y si son minúsculas, las convierte en mayúsculas.
``` psc Funcion resultado<-DireccionInversaYTamano(string)
    Definir resultado Como Caracter;
    resultado = ""
    Para contar = Longitud(string) Hasta 1 Con Paso -1 Hacer
        letra = Subcadena(string, contar, contar);
        Si Mayusculas(letra) = letra Entonces
            letra = Minusculas(letra);
        SiNo
            letra = Mayusculas(letra);
        FinSi
        resultado = resultado + letra;
    FinPara
FinFuncion

Algoritmo ejemploDireccionInversaYTamano
    Imprimir DireccionInversaYTamano("hola");
    Imprimir DireccionInversaYTamano("Jesus");
    Imprimir DireccionInversaYTamano("Docena");
FinAlgoritmo
* agrego una imagen para que se pueda ver mi respuesta.

![image](https://github.com/luciaflortop/core.lucia/assets/132409270/3032860b-b49d-4b1d-ac59-61d11c5b242b)
* ALETA.
* FIN DE MI ALGORITMO DE DIRECCION INVERSA Y TAMAÑO DE SEMANA 4.
