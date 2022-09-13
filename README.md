

## Espumados Prueba Técnica - David Cermeño 2022

En este proyecto se realizó un CRUD para la creación de usuarios y roles, donde cada uno tiene su tabla correspondiente. Dentro de la tabla usuarios podremos exportar un excel con la información correspondiente.

Para este proyecto hay que tener en cuenta lo siguiente.
- [Tener composer instalado].
- [Tener una versión de laravel 7+].
- [Usar Xampp o Wampp para trabajar de manera local].
- [Al registrar en la interfaz de Registro, realizar el registro con el correo 
  "admin@admin.   com" ya que, este sería el Super Administrador.]

Para iniciar el proyecto tenemos que:
- [Crear una base de datos en phpMyAdmin con el mismo nombre que .env].
- [Realizar las migraciones con "php artisan make:migration"]
- [Realizar los seeders con "php artisan db:seed --class=SeederTablaPermisos"].

Dentro de este proyecto se está usando:
- [Laravel-ui-stisla](https://infyom.com/open-source/laravelgenerator/docs/introduction).
- [Spatie](https://spatie.be/docs/laravel-permission/v5/introduction).
- [Laravel Collective](https://laravelcollective.com/docs/6.x/html).
- [Bootstrap].


