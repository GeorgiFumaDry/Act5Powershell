0. Cambia el prompt de PowerShell utilizando la inicial de tu nombre y tu apellido, en mi caso sería:

PS C:\> function prompt {"alopez> "} alopez >

![image](https://github.com/user-attachments/assets/31c4d9c3-8640-4eec-b597-b3ccbe158259)

1. Situado en C:\, crea el directorio SOM y te sitúas en él. Crea los directorios (A1, A2, A3, A11, A111, A112) con una única sentencia y trayectoria relativa.

![image](https://github.com/user-attachments/assets/ed0a08cb-3a6f-42d1-a802-026b8835b43f)

![image](https://github.com/user-attachments/assets/02a8f16c-1028-4e01-8818-f75f5234e2b2)

2. Situado en A111 crea los directorios B1, B2, B3, B31 con una única sentencia y usando trayectoria absoluta.

![image](https://github.com/user-attachments/assets/b70f2786-2975-4f43-879a-b01f1d4c9dd7)

![image](https://github.com/user-attachments/assets/6a162234-c0bc-4e23-aee6-5f247e4fe691)

4. Situado en el directorio A111 crea el fichero texto.txt utilizando trayectoria relativa. Dicho fichero deberá contener el texto: “La fecha de hoy es:”

![image](https://github.com/user-attachments/assets/3fe0d7a8-1f95-4a4e-8b03-b1b98f64c825)

![image](https://github.com/user-attachments/assets/a1779cdc-f164-41ec-aaa3-d2a2285ac743)

6. Situado en el directorio A111, crea en el directorio B31 el fichero fecha.txt utilizando trayectoria relativa. Dicho fichero deberá contener la fecha de hoy. (Utiliza el comando específico para mostrar la fecha actual)

![image](https://github.com/user-attachments/assets/9bbecfa9-ed37-477d-981b-fa5a04ecc726)

![image](https://github.com/user-attachments/assets/653ba83e-80ab-4b7e-8ea4-5ad4fa4979e4)

7. Situado en el directorio A111, crea en B1 un archivo llamado fechahoy.txt que contenga el contenido del archivo texto.txt y del archivo fecha.txt

![image](https://github.com/user-attachments/assets/f3c88a56-6fcb-4eb3-87ac-fdfc57178851)

8. Muévete desde A111 a B1 con una única sentencia. Crea una copia del archivo fechahoy.txt en el directorio A3, esta copia del archivo se tiene que llamar fechahoy.doc

![image](https://github.com/user-attachments/assets/ba32b734-6e96-473c-85c7-c0200557ebbb)

![image](https://github.com/user-attachments/assets/cf8dbfac-17f9-4028-8431-6677bf40544c)

![image](https://github.com/user-attachments/assets/455a69d9-bea0-4f7e-bfde-07024f289ce3)

9. Situado en B1, crea en SOM un archivo llamado arbol.txt que contenga el árbol de directorios y archivos dependientes de SOM.

![image](https://github.com/user-attachments/assets/349cecc9-042c-4251-9440-1f5520917b91)

En este punto del ejercicio deberías tener un árbol de directorios similar al expuesto al comienzo del ejercicio


8. Situado en B31 mueve el archivo fecha.txt a B1 utilizando trayectoria relativa

![image](https://github.com/user-attachments/assets/78784990-9b78-4e0f-a8c8-da3a4e40aa73)

9. Situado en B31 y en una única sentencia mueve B2 a A112 y llámale A1121 (B2 tiene que pasar a llamarse A1121)

![image](https://github.com/user-attachments/assets/f274b256-6cbb-43a1-83f9-0bb66c8683cc)

![image](https://github.com/user-attachments/assets/47b2e577-79b0-49a2-8772-8d5b7621323f)

10. Situado en B31 renombra la carpeta A1121 por NewA1121

![image](https://github.com/user-attachments/assets/027b4ccb-fee4-486b-bda5-78a5c88fd06f)

11. Situado en B31 borra el archivo arbol.txt

![image](https://github.com/user-attachments/assets/2c86b625-4ab8-4bb2-9dd7-46d68fcadc0d)

![image](https://github.com/user-attachments/assets/01bd6637-8fb5-40cc-abeb-7c705a9c752a)

12. Situado en SOM borra los directorios B1, B2 y B3 y los archivos que puedan haber dentro de estos directorios

![image](https://github.com/user-attachments/assets/c6ad4819-7ef3-47b8-b632-d77a774109cd)

![image](https://github.com/user-attachments/assets/67bd643b-6b58-4dbf-ac09-a125a71cf14c)

13. Estando situado en A111 borra A1, A2 y A3

![image](https://github.com/user-attachments/assets/cd1e3d5b-5b7e-4b6b-93eb-8b01bea1e404)

![image](https://github.com/user-attachments/assets/ba927d6f-f035-49bb-9d45-b58187754f8a)

¿Se han borrado todos los directorios y archivos dependientes de SOM?, ¿Por qué?
no, porque estaba A111 en uso

14. Situado en A111 lista los archivos que comiencen por la letra t con extensión .txt

![image](https://github.com/user-attachments/assets/4833a6d1-278d-4620-a040-bb294f371b79)

15. Ejecuta la ayuda del comando prompt

![image](https://github.com/user-attachments/assets/cc2573f1-a61b-463f-b6dd-8d640e3982fa)

16. Cambia el prompt por defecto por miprompt.

![image](https://github.com/user-attachments/assets/4784b1c6-10e8-408d-ae57-971601c2b945)

17. Ejecuta el comando para ver el nombre de equipo y el usuario que lo está usando

![image](https://github.com/user-attachments/assets/10ef5839-3d44-4f29-b97f-c227f3431bcc)

18. Borra el directorio SOM

![image](https://github.com/user-attachments/assets/33db39ac-191f-40d1-9dae-3f4e50876c41)

19. Muestra los comandos utilizados en la sesión.

![image](https://github.com/user-attachments/assets/31548691-b7e2-4795-a4b2-6911a7ff7392)

20. Limpia la consola

![image](https://github.com/user-attachments/assets/ed5e9f17-d2a9-4f75-ba15-27e0e7523409)

![image](https://github.com/user-attachments/assets/e853988d-fec3-4252-90a8-7297dd6dd690)
