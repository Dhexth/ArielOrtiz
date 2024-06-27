# ArielOrtiz
Instrucciones de ejecución:
1. Se despliega "Menu de opciones" a seleccionar por el usuario.

- opcion 1: Asigna saldos aleatorios
- opcion 2: Clasifica los saldos
- opcion 3: Ver estadisticas
- opcion 4: Genera reporte de saldos
- opcion 5: Salir

El usuario debera seleccionar la opcion 1 para poder generar los saldos aleatorios a 10 clientes, de no ser asi el progamara le arrojara un mesaje indicando que debe seleccionar dicha opcion.

Al generar los saldos alearotios el usuario podra interactuar con las opciones siguientes.


Este Programa hace lo siguiente:

* Opcion 1: Genera saldos aleatorios para 10 clientes.
* Opcion 2: Clasifica los saldos en tres rangos: bajos, medios y altos.
* Opcion 3: Calcula y muestra estadísticas avanzadas sobre los saldos (saldo más alto, saldo más bajo, saldo promedio y media geométrica).
* Opcion 4: Genera un reporte detallado de saldos con deducciones y saldo neto, exportándolo a un archivo CSV.
* Opcion 5: Ofrece una opción para salir del programa con un mensaje de despedida.



Procesos del Programa:

1. Importar módulos necesarios:
* random: Para generar saldos aleatorios.
* statistics: Para calcular estadísticas.
* csv: Para trabajar con archivos CSV.
* math.prod: Para calcular el producto de una lista de números (útil para la media geométrica).

2. Generar Saldos Aleatorios:
* Se genera un diccionario donde las claves son nombres y los valores son saldos aleatorios enteros entre 100000 y 500000.

3. Clasificar Saldos:
* Se clasifican los saldos en tres categorías: bajos, medios y altos, basados ​​en los valores de los saldos.

4. Calculadora Media Geométrica:
* Calcula la media geométrica de los saldos usando "math.prod" y el tamaño de la lista de saldos.

5. Calcular estadísticas:
* Calcula y devuelve el saldo más alto, el saldo más bajo, el saldo promedio y la media geométrica de los saldos.

6 . Generar informe CSV:
* Crea y abre un archivo CSV para escribir.
* Escribe la fila de encabezados: ['Cliente', 'Saldo Bruto', 'Impuesto', 'Seguro', 'Otros', 'Saldo Neto'].
* Para cada cliente, calcula las deducciones y el saldo neto y escribe una fila en el archivo CSV.

7. Mostrar Menú de Opciones:
* Muestra el menú de opciones para el usuario.

8. Ejecutar la Opción Seleccionada:
* 1.Asignar saldos aleatorios
* 2.Clasificar Saldos
* 3.Ver estadísticas
* 4.Generar reporte de saldos
* 5.Salir

9. Función Principal:
* Definir los nombres de los clientes.
* Inicia un bucle para mostrar el menú y ejecutar las opciones seleccionadas por el usuario hasta que decida salir.