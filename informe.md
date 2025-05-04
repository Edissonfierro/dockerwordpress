# Informe Semana 5 - Despliegue de WordPress con Docker
## 2. Tiempo de duración
**Tiempo estimado: 60 minutos**
## 3. Fundamentos

### ¿Qué es WordPress?
WordPress es un sistema de gestión de contenidos (CMS) de código abierto que permite crear y administrar sitios web de forma sencilla, sin necesidad de conocimientos avanzados de programación.

### ¿Qué es MySQL?
MySQL es un sistema de gestión de bases de datos relacional de código abierto. WordPress utiliza MySQL para almacenar toda la información del sitio: usuarios, entradas, configuraciones, etc.

### ¿Qué es phpMyAdmin?
phpMyAdmin es una herramienta basada en web que permite administrar bases de datos MySQL de forma visual, a través de un navegador, sin usar comandos.

### ¿Qué es una red personalizada en Docker?
Una red personalizada permite que los contenedores se comuniquen entre sí utilizando sus nombres como si fueran direcciones. Es más seguro y organizado que exponer puertos al público innecesariamente.

### ¿Qué es un volumen en Docker?
Un volumen es una carpeta especial que permite guardar datos aunque el contenedor se borre o reinicie. En este caso, se usó para asegurar la persistencia de WordPress y MySQL.

## 4. Conocimientos previos
- Comandos básicos de Docker (`run`, `network`, `volume`).
- Conceptos de red y puertos.
- Conocimiento básico de base de datos y CMS.
- Acceso a navegador y terminal.

## 5. Objetivos a alcanzar
- Crear una red personalizada llamada `eddie_red1`.
- Crear volúmenes para WordPress y MySQL.
- Levantar contenedores de WordPress, MySQL y phpMyAdmin.
- Verificar la correcta conexión entre todos los servicios.
- Acceder al asistente de instalación de WordPress desde el navegador.

## 6. Equipo necesario
- Computador con Windows/Linux/MacOS.
- Docker instalado.
- Conexión a internet.
- Navegador web (Chrome, Firefox, etc).

## 7. Material de apoyo
- Documentación oficial de [Docker](https://docs.docker.com)
- Documentación de [phpMyAdmin](https://docs.phpmyadmin.net/)
- Documentación oficial de [MySQL](https://dev.mysql.com/doc/)
- Documentación oficial de [WordPress](https://wordpress.org/support/)


## 8. Procedimiento
·· Primer paso 
Eliminar los contenedores existentes para evitar confusiones y hacer un trabajo limpio.
![img01](https://github.com/Edissonfierro/dockerwordpress/blob/main/1.jpg)


## 9. Resultados esperados
WordPress accesible en http://localhost:8000

phpMyAdmin accesible en http://localhost:8080

Conexión exitosa entre WordPress y MySQL

Acceso al asistente de instalación de WordPress

Contenedores funcionando correctamente

Datos almacenados de forma persistente en volúmenes


## 10. Diagrama
## 11. Evidencia de funcionamiento

## 12. Bibliografía
Docker. (n.d.). Docker networking overview. https://docs.docker.com/network/

phpMyAdmin. (n.d.). phpMyAdmin documentation. https://docs.phpmyadmin.net/

MySQL. (n.d.). MySQL 8.0 reference manual. https://dev.mysql.com/doc/

WordPress. (n.d.). WordPress support. https://wordpress.org/support/
