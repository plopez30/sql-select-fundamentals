# sql-select-fundamentals
Módulo4-UNIDAD1

Pregunta 1. 
Utilizar el SELECT * trae todas las columnas, incluso las que no necesito. Esto causa más consumo de memoria y relentiza el tráfico.
Si se agrega columnas nuevas, también las mostrará aunque no sean necesarias. Causando lo mismo que mencioné arriba.
Además, se exponen todos los datos que tiene esa tabla. 

Pregunta 2.
Los alias son importantes porque ayudan a que los datos/tablas/análisis sean comprensibles por personas que no están en el área de data. De esta manera, la información llega "traducida" y de forma mas eficiente a los stakeholders.  

Ejemplo:
total_amount puede generar confusión en personas del área de finanzas que no hablen inglés. Usando el alias (AS en SQL) lo cambiamos para que sea mejor interpretado (por ejemplo: monto_total).
