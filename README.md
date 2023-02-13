# JSON WEB TOKEN
## API Auth

Proyecto para demostrar como ejemplo una implementación sencilla con JWT
Se siguió la documentación del paquete de [JWT-Auth](http://https://jwt-auth.readthedocs.io/en/develop/ "JWT-Auth").

Para configurar este proyecto en su entorno local descargue el repositorio
E inicie el proyecto la instalación de las dependencias composer:

```bash
composer install
```

y corra el servidor con **php run serve**

con su aplicación de preferencia por ejemplo **Postman** puede realizar las peticiones a las siguientes rutas

- POST	/api/register
- POST	/api/login
- GET	/api/users

las rutas POST tienen validaciones sencillas incluidas
La ruta protegida con JWT es **GET /api/users**

Gracias por ver