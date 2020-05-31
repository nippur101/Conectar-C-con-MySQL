# Conectar-C-con-MySQL
Pasos para conectar C con Codeblocks con MySQL

Bajar mysql-connector-c-6.1.11-win32  - (Windows (x86, 32-bit), ZIP Archive)
https://downloads.mysql.com/archives/get/p/19/file/mysql-connector-c-6.1.11-win32.zip

En CodeBlocks
Project/Build Options |Search Directories| add Buscar la carpeta include dentro del archivo descomprimido(mysql-connector-c-6.1.11-win32.zip)

Project/Build Options |Linker Settings| add Buscar la carpeta lib/libmysql

ANTES DE COPIAR EL CODIGO DE CONECCION PROBAR SI FUNCIONA LA LIBRERIA #include <mysql.h>

EN LA BASE DE DATOS AGREGAR EL COMANDO-----> ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY '1234';
(AGREGAR EL PASSWORD DESEADO PARA CONECTAR)

COPIAR EL CODIGO DE CONECCION cambiar base de datos o tablas a leer.


