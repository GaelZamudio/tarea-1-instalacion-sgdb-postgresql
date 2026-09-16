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
<img width="733" height="694" alt="Pasted image 20260915205220" src="https://github.com/user-attachments/assets/c6270017-a67b-47ab-b246-83c4b4d5cf43" />

Bastará con dar clic en "Downloads", y esto nos llevará a la siguiente página:
<img width="1919" height="508" alt="Pasted image 20260915205254" src="https://github.com/user-attachments/assets/5490cbae-7861-4360-883e-51b00efa4476" />
En esta página daremos clic en nuestro sistema operativo (en mi caso Windows) y eso nos dirigirá a la siguiente página:
<img width="1919" height="475" alt="Pasted image 20260915210714" src="https://github.com/user-attachments/assets/1439d9ef-2ad5-461b-ae42-9f858a5d1d8d" />

Aquí simplemente damos clic en "Download the installer", nos dirigirá a una página como esta:
<img width="1919" height="687" alt="Pasted image 20260915210824" src="https://github.com/user-attachments/assets/53b36e94-8d27-4ed6-a255-e3da2eab27f5" />
Esta página nos muestra las diferentes versiones de PostgreSQL, en este caso descargaremos la más reciente dándole clic en el botón señalado con el círculo rojo (esto es para windows, para instalarlo en otro OS simplemente se tiene que dar clic al botón de ese OS)
Posteriormente, se descargará el ejecutable:

<img width="76" height="106" alt="Pasted image 20260915211205" src="https://github.com/user-attachments/assets/1674fafb-e2af-4242-be4f-a014460733eb" />

Sólo debemos dar doble clic para ejecutarlo. Se nos abrirá la siguiente ventana:

<img width="560" height="442" alt="Pasted image 20260915211304" src="https://github.com/user-attachments/assets/77611632-8c1b-41e0-b4cd-ddc3788d6314" />

Damos clic en "siguiente":

<img width="554" height="438" alt="Pasted image 20260915211319" src="https://github.com/user-attachments/assets/00c6a4d1-936a-412d-b06e-8dd5ef6fc683" />

Especificamos el directorio en el que queramos instalar PostgreSQL, pero se recomienda dejar el default.
<img width="551" height="431" alt="Pasted image 20260915211358" src="https://github.com/user-attachments/assets/fe0337f9-aeed-43b2-9cbe-2a7f6aa65aae" />

Aquí podemos desmarcar Stack Builder (no lo utilizamos para este curso) y dar clic en "siguiente":

<img width="551" height="430" alt="Pasted image 20260915211445" src="https://github.com/user-attachments/assets/7f5a12b6-6609-47b2-94a5-c74816fe58f0" />

Nuevamente, damos clic en "siguiente":

<img width="554" height="437" alt="Pasted image 20260915211522" src="https://github.com/user-attachments/assets/016c7cce-312a-4dee-8a36-7e50f20f9b52" />

Volvemos a cliquear "siguiente":

<img width="556" height="434" alt="Pasted image 20260915211543" src="https://github.com/user-attachments/assets/4b206a6d-fdf8-459f-9555-906cbe8678f1" />

Damos clic en "siguiente" una última vez y el programa comenzará su instalación:

<img width="548" height="430" alt="Pasted image 20260915211602" src="https://github.com/user-attachments/assets/3f7f8636-3cf4-4784-8369-3dcfde39e4cf" />

Posteriormente sólo damos clic en "finalizar" y el SGDB estará listo para usar.
Para comprobar que se instaló correctamente podemos ejecutar el siguiente comando en la terminal (CMD en windows)
```
psql -V
```
Nos debería devolver algo como:

<img width="219" height="62" alt="Pasted image 20260915214304" src="https://github.com/user-attachments/assets/b8f5a467-1441-4dc0-acab-ea0321047a34" />

Y con esto quedaría finalizada la instalación del SGDB PostgreSQL.
# Referencias
- Amazon Web Services. (s. f.). _¿Qué es DBMS?_ [https://aws.amazon.com/what-is/dbms/](https://aws.amazon.com/what-is/dbms/)
- IBM. (s. f.). _What is a database management system?_ IBM Documentation. [https://www.ibm.com/docs/en/zos-basic-skills?topic=zos-what-is-database-management-system](https://www.ibm.com/docs/en/zos-basic-skills?topic=zos-what-is-database-management-system)
- PostgreSQL Global Development Group. (s. f.). _PostgreSQL 17.0 Documentation: Installation_. [https://www.postgresql.org/docs/current/tutorial-install.html](https://www.postgresql.org/docs/current/tutorial-install.html)
