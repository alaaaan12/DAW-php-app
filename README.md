# DAW PHP App

Este proyecto es una aplicación web en PHP para la gestión de productos. Incluye funcionalidades para listar, modificar y actualizar productos en una base de datos.

## Requisitos

- PHP 7.4 o superior
- Servidor web (Apache, Nginx, etc.)
- MySQL 5.7 o superior

## Instalación

1. Clona el repositorio en tu máquina local:
    ```bash
    git clone https://github.com/tu-usuario/DAW-php-app.git
    ```

2. Configura la base de datos:
    - Crea una base de datos llamada `la_meva_botiga`.
    - Importa el archivo `database.sql` para crear las tablas necesarias.

3. Configura la conexión a la base de datos en el archivo `Connexio.php`:
    ```php
    // filepath: /c:/Users/adams/Documents/GitHub/DAW-php-app/Connexio.php
    private $host = "localhost";
    private $usuario = "root";
    private $contraseña = "";
    private $baseDatos = "la_meva_botiga";
    ```

4. Inicia el servidor web y accede a la aplicación desde tu navegador.

## Estructura del Proyecto

- `Principal.php`: Muestra la lista de productos.
- `Modificar.php`: Muestra el formulario para modificar un producto.
- `Actualitzar.php`: Actualiza un producto en la base de datos.
- `Header.php`: Muestra el encabezado de la página.
- `Footer.php`: Muestra el pie de página.
- `Connexio.php`: Maneja la conexión a la base de datos.

## Documentación

La documentación del proyecto está disponible en el directorio `docs`. Puedes acceder a ella abriendo el archivo `docs/index.html` en tu navegador.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request para discutir cualquier cambio que desees realizar.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.
