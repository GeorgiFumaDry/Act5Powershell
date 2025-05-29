0. Cambia el prompt de PowerShell utilizando la inicial de tu nombre y tu apellido, en mi caso sería:

PS C:\> function prompt {"alopez> "} alopez >

![image](https://github.com/user-attachments/assets/31c4d9c3-8640-4eec-b597-b3ccbe158259)

1. Situado en C:\, crea el directorio SOM y te sitúas en él. Crea los directorios (A1, A2, A3, A11, A111, A112) con una única sentencia y trayectoria relativa.

![image](https://github.com/user-attachments/assets/ed0a08cb-3a6f-42d1-a802-026b8835b43f)

![image](https://github.com/user-attachments/assets/02a8f16c-1028-4e01-8818-f75f5234e2b2)

2. Situado en A111 crea los directorios B1, B2, B3, B31 con una única sentencia y usando trayectoria absoluta.

![image](https://github.com/user-attachments/assets/3833c66f-a3bf-4b04-863b-777b7ecf6fb5)

![image](https://github.com/user-attachments/assets/ad9e6b2a-4db8-4736-bec8-812560440955)

4. Situado en el directorio A111 crea el fichero texto.txt utilizando trayectoria relativa. Dicho fichero deberá contener el texto: “La fecha de hoy es:”

![image](https://github.com/user-attachments/assets/3fe0d7a8-1f95-4a4e-8b03-b1b98f64c825)

![image](https://github.com/user-attachments/assets/a1779cdc-f164-41ec-aaa3-d2a2285ac743)

6. Situado en el directorio A111, crea en el directorio B31 el fichero fecha.txt utilizando trayectoria relativa. Dicho fichero deberá contener la fecha de hoy. (Utiliza el comando específico para mostrar la fecha actual)



7. Situado en el directorio A111, crea en B1 un archivo llamado fechahoy.txt que contenga el contenido del archivo texto.txt y del archivo fecha.txt

8. Muévete desde A111 a B1 con una única sentencia. Crea una copia del archivo fechahoy.txt en el directorio A3, esta copia del archivo se tiene que llamar fechahoy.doc

9. Situado en B1, crea en SOM un archivo llamado arbol.txt que contenga el árbol de directorios y archivos dependientes de SOM.


En este punto del ejercicio deberías tener un árbol de directorios similar al expuesto al comienzo del ejercicio


8. Situado en B31 mueve el archivo fecha.txt a B1 utilizando trayectoria relativa

9. Situado en B31 y en una única sentencia mueve B2 a A112 y llámale A1121 (B2 tiene que pasar a llamarse A1121)

10. Situado en B31 renombra la carpeta A1121 por NewA1121

11. Situado en B31 borra el archivo arbol.txt

12. Situado en SOM borra los directorios B1, B2 y B3 y los archivos que puedan haber dentro de estos directorios

13. Estando situado en A111 borra A1, A2 y A3

¿Se han borrado todos los directorios y archivos dependientes de SOM?, ¿Por qué?

14. Situado en A111 lista los archivos que comiencen por la letra t con extensión .txt

15. Ejecuta la ayuda del comando prompt

16. Cambia el prompt por defecto por miprompt.

17. Ejecuta el comando para ver el nombre de equipo y el usuario que lo está usando

18. Borra el directorio SOM

19. Muestra los comandos utilizados en la sesión.

20. Limpia la consola
