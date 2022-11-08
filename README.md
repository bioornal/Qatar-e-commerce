![HenryLogo](https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png)

# Final Project Henry - Qatar e-commerce


## Objetivos del Proyecto

- Construir una App utlizando React, Redux, Node y Sequelize.
- Afirmar y conectar los conceptos aprendidos en la carrera.
- Aprender mejores prácticas.
- Aprender y practicar el workflow de GIT.
- Investigación y puesta en práctica de nuevas tecnologías que no se enseñan en el bootcamp.
- Adquirir experiencia en la construcción de este proyecto trabajando en equipo, coordinando tareas, tiempos, utilizando metodología Scrum.
- Sobreponerse al reto de integrar un grupo de personas totalmente desconocidas, con las cuales se deberán compartir extensas horas y entablar relaciones eficaces.

## Horarios y Fechas

El proyecto tuvo una duración máxima de tres semanas y media. Se realizó en Septiembre/Noviembre 2022

## Comenzando

1. Se creo un boilerplate con React-create-app y se inicializo un server back end con Sequelize y Express


## BoilerPlate

El boilerplate cuenta con dos carpetas: `api` y `client`. En estas carpetas estará el código del back-end y el front-end respectivamente.

En `api` crear un archivo llamado: `.env` que tenga la siguiente forma:

```env
DB_USER=usuariodepostgres
DB_PASSWORD=passwordDePostgres
DB_HOST=localhost
```

Reemplazar `usuariodepostgres` y `passwordDePostgres` con tus propias credenciales para conectarte a postgres. Este archivo va ser ignorado en la subida a github, ya que contiene información sensible (las credenciales).

Adicionalmente será necesario que creen desde psql una base de datos llamada `ecommerce`



## Enunciado

La idea general es crear una aplicación en la cual se pueda ver información de  distintos productos para venta sobre Qatar 2022 utilizando la api creada en back a partir de un JSON hardcodeado y a partir de ella poder, entre otras cosas:

- Buscar productos
- Filtrarlos / Ordenarlos
- Crear - MOdificar - Eliminar productos
- Poder comprar dichos productos, por ende manejar un carrito de compras
- El cliente y un admin debe poder loguarse para hacer compras y hacer modificaciones respectivamente


#### Tecnologías utilizadas

- [ ] React
- [ ] Redux
- [ ] Bootstrap
- [ ] Javascript
- [ ] React-hook-form
- [ ] Auth0
- [ ] Express
- [ ] Sequelize - Postgres

![web](https://user-images.githubusercontent.com/88909356/200628592-8fbc0ea2-1545-4544-82a9-5460fa10c811.png)

![web1](https://user-images.githubusercontent.com/88909356/200629361-f38037f3-8114-4134-8384-096047ac07d6.png)

![web2](https://user-images.githubusercontent.com/88909356/200629425-bad115e4-de09-4c04-b5b1-11fe4320c2c2.png)

![web3](https://user-images.githubusercontent.com/88909356/200629466-3055cebe-e344-4d0b-a924-95795612c0c8.png)

![web4](https://user-images.githubusercontent.com/88909356/200629497-15f42282-fe96-4d3c-9e44-4c43fd3a906d.png)
