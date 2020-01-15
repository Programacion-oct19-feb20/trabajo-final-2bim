# Fundamentos de programación
## Segundo Bimestre
### Trabajo Final Individual 

Generar una aplicación que permita gestionar cuentas de ahorros de clientes de un banco; en la aplicación se debe gestionar:
- El ingreso de nuevos clientes.
- Manejo de depósitos en cuentas de clientes.
- Manejo de retiros en cuentas de clientes.
- Certificados de saldos de clientes.
- Reporte de saldos de los clientes del banco.

#### Observaciones:
- En un archivo denominado clientes.txt existe un listado previo de clientes del banco ya registrados; así como los archivos (cuentas) por cada uno de los clientes que existan en el archivo llamado clientes.txt con su saldo inicial. La cuenta inicial es creada con un saldo de $1000.
- Para el ingreso de nuevos clientes se debe pedir información como:
	- nombres
	- apellidos
	- cedula

La cédula será el id de la cuenta de ahorros. La cuenta del cliente será creada a través de la creación de un archivo denominado:

cedula.txt y cuyo contenido será:
```
saldo|1000.0
```

Además la información se debe agregar a un archivo denominado clientes.txt

- Para el manejo de depósitos en las cuentas de ahorro, considerar:
	- Pedir el número de cuenta del cliente (cédula).	
	- Si la cuenta existe se procede a pedir el valor del depósito.
	- El valor de depósito se debe registrar en el archivo que registra las transacciones de la cuenta. Ejemplo, si existe un cuenta llamada 1234556.txt previamente creada y se realiza un depósito de un valor de $200,  el contenido del archivo será:
```
saldo|1000.0
depósito|200
```

- Para el manejo de retiros de las cuentas de ahorro, considerar:

	- Pedir el número de cuenta del cliente (cédula).	
	- Si la cuenta existe se procede a pedir el valor del retiro.
	- Se obtiene el saldo de la cuenta.
	- Si el valor de retiro es menor o igual al saldo se realiza la transacción.
	- El valor de retiro se debe registrar en el archivo que registra las transacciones de la cuenta. Ejemplo, si existe un cuenta llamada 1234556.txt previamente creada y se realiza un retiro de un valor de $400,  el contenido del archivo será:
```
saldo|1000.0
depósito|200
retiro|400
```

- Para la certificación del saldo del cliente, considerar:
	- Pedir el número de cuenta del cliente (cédula).	
	- Si la cuenta existe se procede, se obtiene el saldo de la cuenta y se debe generar un archivo con el siguiente contenido:
	Ejemplo, si existe un cuenta llamada 1234556.txt con las siguientes transacciones registradas:
```
saldo|1000.0
depósito|200
retiro|400
```

El saldo sería $800; el nombre del archivo será: certificado_ 1234556.txt; el contenido del archivo tiene lo siguiente:
```
Certificado de Saldos

Identificación del Cliente:  1234556
Saldo a la fecha: $800
```

- El reporte de saldos de todos los clientes del banco será un nuevo archivo con el siguiente contenido:

	- Archivo llamado saldos_clientes.txt:
```
1234556|800
1234557|700
4234556|600
1238556|200
```

#### Tecnologías y herramientas a usar:

- Manejo de versiones de código a través de github (repositorio dado por el docente a través de https://classroom.github.com/).
- Lenguaje de programación Java.
- IDE de programación Netbeans.
- El número de clases y métodos usados bajo el lenguaje Java queda a criterio de la solución que se generará.
- El código generado debe cumplir con lo estándares considerados el ciclo académico.
- Incluir documentación a la solución planteada.

#### Fecha de presentación:
- 30 de enero de 2020
