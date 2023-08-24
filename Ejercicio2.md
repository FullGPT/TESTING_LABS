# Ejercicio 2 - Error en el método ‘GetCotizacion’*
**Descripción:**
El servicio ASMX se desplegó a través del IDE Microsoft Visual Studio 2022 y bajo el framework ASP.NET en el navegador Microsoft Edge. La compilación se realizó en una laptop ASUS con un procesador Intel(R) Core(TM) i5 y demoró menos de un minuto.

**Test funcional:** No procede la integración a producción.<br><br>
El código no pasa a producción ni a despliegue porque se encontró un error de compilación (error BC30035: Syntax error) en la línea 20: “RE”. Este error no permite devolver el equivalente del tipo de moneda ingresada. Se devuelve al área de desarrollo.

## Recomendaciones
El error de compilación se debe a una mala redacción en la sección de casos en el método "GetCotizacion". Los casos no están escritos correctamente y la sintaxis es incorrecta. Para solucionar dicho error, se debe agregar al inicio de la línea 20 la palabra “Case”, antes de “RE”.
