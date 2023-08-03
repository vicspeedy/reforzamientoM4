# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

# Paginas Estaticas
-- Home
-- Terminos
-- Privacidad
-- Contacto

# Modelos
-- Producto
-- Reseña
-- Usuario
-- Categoria 

# Proudcto
* id
* Nombre
* Codigo
* Categoria
* Descripcion
* Precio
* Enlace
* Foto 

# GIT Ramas
* develop = Desarrollo -> Local
* staging = QA -> Local - Nube
* main = Produccion -> Nube
* Nueva Rama: git branch feat/nombreRama Ej: git branch feat/staticPage
* Moverse Rama: git checkout feat/staticPage

rails new reforzamientoM4 -d postgresql && cd reforzamientoM4
Configurar database.yml
git add .
git commit -m "First commit"
rails db:create
git remote add origin https://github.com/vicspeedy/reforzamientoM4.git
git push -u origin main
git branch feat/staticPage
git checkout feat/staticPage
rails g controller Pages home terms privacy

