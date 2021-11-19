# Ejemplo de un servidor web en express

## Caracteristicas 
* Instalacion automatizada por medio de scripts personalizados.
* Crud de productos (permite crear, editar, eliminar y listar).
* Registro y autenticacion de usuarios.
* Manejo de sesion de usuarios y mensajes (Proximamente mensajes emergentes).
* Implementacion de patron de diseño MVC con una capa de servicio DAO entre modelo y controlador

## Ejecucion del proyecto

1. iniciar un servidor mysql.
2. crear archivo .env y poner los datos del .env.example con tus datos correspondientes.
3. En la raiz del proyecto abrir un terminal de comandos
4. Ejecutar npm install.
5. Si llega a fallar la instalacion ejecute npm  i env-cmd y despues npm install nuevamente.
6. LISTO, en el terminal vera una direccion de puerto, abra una ventana del explorador y valla a la direccion localhost:"direccion del puerto".


## Proximas Caracteristicas
* Api para listado de productos y detalle indivudual.
* Api para listado de usuarios.
* Mejoras en el diseño visual.
* Imagenes servidas desde el Servidor (valga la redundancia...).
