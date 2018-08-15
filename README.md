# mysql_count_rows
Script bash para contar las filas de todas las tablas de una base de datos mysql y guardarlas en una archivo csv

Para usarlo ejecutar

chmod +x mysql_count_rows

cp mysql_count_rows /usr/local/bin

O usar directamente como ./mysql_count_rows

Modo de empleo: 
mysql_count_rows db user \[pass\]

Cuenta el numero de registro de todas las tablas de una base de datos mysql
Si no se proporciona un password se pedirá ingresarlo, pero sin mostrarlo.
