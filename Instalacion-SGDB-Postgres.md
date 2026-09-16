# Introducción
### ¿Qué es un SGBD?
Un Sistema Gestor de Bases de Datos es, en esencia, una tecnología (software) que facilita el proceso de realizar operaciones en una base de datos. Ayuda a almacenar los datos, aumenta la disponibilidad de éstos y además mejora el rendimiento (optimiza las consultas). Un SGDB ayuda a administrar volúmenes de datos ya sean grandes o pequeños.
### ¿Para qué se necesita un SGDB?
El uso de un SGDB tiene ciertas ventajas, tales como:
- **Funcionar como un todo en uno**: aunque algunos SGDBs incluyen más funciones que otros, podemos decir que la mayoría permite realizar consultas, actualizaciones en la base de datos, copias de seguridad y validación y cifrado de datos.
- **Brindar estructura**: permite que los usuarios se centren en aprender la lógica de consultas y demás funciones sin tener que preocuparse por lo que ocurre en la programación de bajo nivel involucrada. Esto sirve para que los usuarios puedan tratar diferentes bases de datos con sólo aprender a usar un SGDB.
- **Mantener los datos organizados**: garantiza que los datos estén organizados en el formato descrito y puedan manipularse sin preocuparse por una falla operativa o de la base de datos.
# Cómo instalar un SGDB (PostgreSQL)
A continuación se muestra el proceso de instalación de un SGDB, el cual es PostgreSQL, ya que es el SGDB que usaremos durante todo el curso.
### 1. Descargar el instalador
Primero, buscando "PostgreSQL download" en internet nos encontraremos con una página que se ve algo así:
![[Pasted image 20260915205220.png]]
Bastará con dar clic en "Downloads", y esto nos llevará a la siguiente página:
![[Pasted image 20260915205254.png]]
En esta página daremos clic en nuestro sistema operativo (en mi caso Windows) y eso nos dirigirá a la siguiente página:
![[Pasted image 20260915210714.png]]

Aquí simplemente damos clic en "Download the installer", nos dirigirá a una página como esta:
![[Pasted image 20260915210824.png]]
Esta página nos muestra las diferentes versiones de PostgreSQL, en este caso descargaremos la más reciente dándole clic en el botón señalado con el círculo rojo (esto es para windows, para instalarlo en otro OS simplemente se tiene que dar clic al botón de ese OS)
Posteriormente, se descargará el ejecutable:
![[Pasted image 20260915211205.png]]
Sólo debemos dar doble clic para ejecutarlo. Se nos abrirá la siguiente ventana:
![[Pasted image 20260915211304.png]]
Damos clic en "siguiente":
![[Pasted image 20260915211319.png]]
Especificamos el directorio en el que queramos instalar PostgreSQL, pero se recomienda dejar el default.
![[Pasted image 20260915211358.png]]
Aquí podemos desmarcar Stack Builder (no lo utilizamos para este curso) y dar clic en "siguiente":
![[Pasted image 20260915211445.png]]
Nuevamente, damos clic en "siguiente":
![[Pasted image 20260915211522.png]]
Volvemos a cliquear "siguiente":
![[Pasted image 20260915211543.png]]
Damos clic en "siguiente" una última vez y el programa comenzará su instalación:
![[Pasted image 20260915211602.png]]
Posteriormente sólo damos clic en "finalizar" y el SGDB estará listo para usar.
Para comprobar que se instaló correctamente podemos ejecutar el siguiente comando en la terminal (CMD en windows)
```
psql -V
```
Nos debería devolver algo como:
![[Pasted image 20260915214304.png]]
Y con esto quedaría finalizada la instalación del SGDB PostgreSQL.
# Referencias
- Amazon Web Services. (s. f.). _¿Qué es DBMS?_ [https://aws.amazon.com/what-is/dbms/](https://aws.amazon.com/what-is/dbms/)
- IBM. (s. f.). _What is a database management system?_ IBM Documentation. [https://www.ibm.com/docs/en/zos-basic-skills?topic=zos-what-is-database-management-system](https://www.ibm.com/docs/en/zos-basic-skills?topic=zos-what-is-database-management-system)
- PostgreSQL Global Development Group. (s. f.). _PostgreSQL 17.0 Documentation: Installation_. [https://www.postgresql.org/docs/current/tutorial-install.html](https://www.postgresql.org/docs/current/tutorial-install.html)