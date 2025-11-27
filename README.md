# taller08

### Problame 01
> Analiza el archivo .txt y pasar a lenguaje JAVA, usar variables en Snake-Case

### Problema 02
> En una campaña médica preventiva organizada por el Ministerio de Salud, se realiza un control de signos vitales a todas las personas que acuden voluntariamente. Cada vez que llega un ciudadano, el personal registra sus datos en el sistema. No se sabe cuántas personas asistirán en total, por lo que el sistema debe permitir el registro continuo hasta que el usuario indique que desea detener el proceso.

> De cada ciudadano se debe ingresar: nombres completos, edad, temperatura corporal en °C y frecuencia cardíaca (latidos por minuto), presión arterial diastólica (además se la debe catalogar como presión baja, normal, elevada mínima, elevada máxima)
> El sistema debe acumular los datos de todos los ciudadanos válidos. Si la edad ingresada es menor de 5 años, ese registro no se considera, no deben pedirse ni temperatura ni frecuencia cardíaca, ni presión  arterial y no debe incluirse en los reportes ni promedios.

> Cuando el usuario indique que desea detener el registro, el sistema debe mostrar un único reporte final que incluya: Un listado completo de todas las personas registradas.

> * El promedio de edades.
> * El promedio de temperatura corporal convertida a grados Fahrenheit.
> Fórmula:
> F = C × 9/5 + 32
> El promedio de frecuencias cardíacas.
> El reporte debe permitir al equipo de salud evaluar las tendencias generales observadas durante la jornada.

> Consideraciones: Debe imprimirse solamente un reporte final.

> En relación a la presión
> * 60 - 80 normal
> * mayor a 80 y menor a 100 elevada mínima
> * mayor o igual a 100 elavada máxima
> * menor a 60 presión mal tomada

### Problema 03

>  Una ferretería necesita registrar 4 herramientas que llegaron en un nuevo lote. Por cada herramienta se debe ingresar:
> * Nombre de la herramienta, Precio unitario, Tipo de herramienta: 1 = Construcción, 2 = Electricidad, 3 = Jardinería,
> Para cada herramienta se aplican reglas internas:

> 1) Si el precio es menor o igual a $0: El valor base será $0, El valor del impuesto será $0, El impuesto aplicado será 0%, El valor final será $0

> 2) Si el precio es mayor a 0: Si el tipo es 1 o 2 → aplicar impuesto del 8%, Si el tipo es 3 → aplicar impuesto del 10%, En cualquier otro caso → aplicar impuesto del 18%

> El sistema deberá generar un reporte final como el siguiente:
```
Listado de herramientas
1. Taladro (Electricidad), valor base: $120, impuesto (8%): $9.60, valor final: $129.60
2. Pala (Jardinería), valor base: $18, impuesto (10%): $1.80, valor final: $19.80
3. Brochas (Sin Categoría), valor base: $10, impuesto (18%): $1.80, valor final: $11.80
4. Lijas (Sin Categoría), valor base: $0, impuesto (0%): $0, valor final: $0.00
```
