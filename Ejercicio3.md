 # Ejercicio 3 - Error en Metodo ‘FahrenheitToCelcius’
Se desplegó a través de Internet Information Services (IIS) Express en su versión 10.0. El framework ASP.NET utilizado en su versión 4.0 en el navegador Opera (v.101).

 # Test funcional: No procede la integración a producción.

El servicio Ejercicio3.asmx obtiene un error de compilación en la línea 17: “ ((Fahrenheit - 32) * 5) / 9”. 

 # Recomendaciones
 
El error de compilación en el código se debe a que falta la instrucción Return en el cuerpo de la función FahrenheitToCelsius. Para solucionar el error, se debe asegurar de agregar Return antes de las fórmulas de conversión para que el resultado de la operación se devuelva como el valor de retorno de la función.
