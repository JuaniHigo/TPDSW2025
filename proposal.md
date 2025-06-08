# Propuesta TP DSW

## Grupo
### Integrantes
* 49951 - Higonet Juan Ignacio
* 48453 - Mercado Martin
* 49620 - Sola Amparo
* 50264 - Ortiz Daiana

### Repositorios
* [frontend app](https://github.com/JuaniHigo/TPDSW-frontend)
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
|CRUD simple|1. CRUD Usuario<br>2. CRUD Tipo Entrada<br>3. CRUD Equipos<br>4.CRUD Socio|
|CRUD dependiente|1. CRUD Partidos {depende de} equipos y estadios<br>2.CRUD sector<br>3.CRUD estadio|
|Listado<br>+<br>detalle| 1. Listado de partidos con detalle (Ver fecha, hora, equipos, estadio y botón para comprar entrada.)<br> 2. Listado de entradas del usuario (El usuario ve sus entradas compradas con información del partido, QR, ubicación, etc.) 
|CUU/Epic|1. Comprar una entrada para un partido<br>2. Notificacion de fechas de partido|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Usuario<br>2. CRUD Tipo Entrada<br>3. CRUD Equipos<br>4.CRUD Socio|
|CUU/Epic|1. Comprar una entrada para un partido<br>2.Metodos de pago<br>3.Sancionar socios|


