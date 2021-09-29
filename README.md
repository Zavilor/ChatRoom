# ChatRoom

Proyecto integrador / Tecnicas Avanzadas de Programación - UP
Alumno: Rettori Juan Francisco
Legajo: 96773
Profesora: María Belén Alegre

Consideraciones:
  * El usuario debe loguearse y seleccionar la sala a la cual ingresar
  * Enviar mensajes a quienes esten conectados
  * Al loguearse ver mensajes no leídos
  * Al retirarme poder elegir borrar todos mis mensajes

Plan de trabajo:
Aplicación Web de chat en tiempo real integrando socket.io.
Tecnologías aplicables:
- Front End:
  * HTML
  * CSS
  * JavaScript
  * Jquery
- Back End:
  * Node JS
- Frameworks:
  * Express JS
  * Bootstrap (CSS)
- Patrón de diseño: MVC - Model View Controller
- Motor de vistas: EJS
- Desarrollo de base de datos: MySQL

Modelo de datos:

TABLAS:
- Usuarios
  * id_user INT (PK) not null
  * nickname VARCHAR(20) not null
  * passwd VARCHAR(20) not null
- Mensajes
  * id_msg INT (PK) not null
  * id_sala INT not null
  * msg VARCHAR (100) not null
  * date DATETIME not null
  * status INT not null
  * delete_date DATETIME null
- Salas
  * id_sala INT (PK) not null
  * name VARCHAR (20)
  



