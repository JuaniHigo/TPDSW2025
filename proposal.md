# Propuesta TP DSW

## Grupo
### Integrantes
* 49951 - Higonet Juan Ignacio
* 48453 - Mercado Martin
* 49620 - Sola Amparo
* 50264 - Ortiz Daiana

### Repositorios
* [frontend app]()
* [backend app]()
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema
### Descripción
Kicket es una página web para la venta online de entradas a partidos de fútbol. Los usuarios podrán ver el calendario de encuentros, elegir sus asientos y comprar entradas de forma rápida y segura. La plataforma incluirá registro de usuarios, distintos métodos de pago y confirmación por correo electrónico. Su objetivo es facilitar el acceso a entradas, evitando filas y optimizando la experiencia del hincha.
### Modelo
![WhatsApp Image 2025-04-11 at 11 12 19](https://github.com/user-attachments/assets/7bc37322-09f7-40e9-87ba-777df41c6276)

https://app.diagrams.net/#G1cc-0-RFMqh4eRY1Vh28ElXyF7EeMj-0q#%7B%22pageId%22%3A%22B9eb_MdfH_icAN6wSzJy%22%7D

## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad|
|CRUD dependiente|1. CRUD Habitación {depende de} CRUD Tipo Habitacion<br>2. CRUD Cliente {depende de} CRUD Localidad|
|Listado<br>+<br>detalle| 1. Listado de habitaciones filtrado por tipo de habitación, muestra nro y tipo de habitación => detalle CRUD Habitacion<br> 2. Listado de reservas filtrado por rango de fecha, muestra nro de habitación, fecha inicio y fin estadía, estado y nombre del cliente => detalle muestra datos completos de la reserva y del cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad<br>4. CRUD Provincia<br>5. CRUD Habitación<br>6. CRUD Empleado<br>7. CRUD Cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva<br>3. Realizar el check-out y facturación de estadía y servicios|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|

