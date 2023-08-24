# Ejercicio 4 - Error en el método dameCita()

El archivo ‘Ejercicio4.asmx fue ejecutado en el entorno Visual Studio, haciendo uso del framework ASP .NET en su versión 4.0 en el navegador Brave
***
## Conclusion
En base a los errores de sintaxis y el error durante la ejecución del servicio, no es posible que este sea enviado a producción. Se sugiere revisar los errores.

## Recomendaciones
Se recomienda como solución a este problema la colocación de llaves que engloben el contexto del método “dameCita()”
Por último, no olvidar las buenas prácticas de nomenclatura en el título de los métodos creados, recalcando que deben comenzar con una letra en mayúscula.
```
[WebMethod]
 public String DameCita() {
  String [] citas = {
   "No hay mal que por bien no venga",
   "FRASE DE PRUEBA 2",
   "No por mucho madrugar amanece mas temprano"};
  Random random = new Random();
  int numCita = random.Next(0,3);
  return (citas[numCita]);
 }
```
