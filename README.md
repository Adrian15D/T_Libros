<h1 align="center">Proyecto Individual Front-end</h1>
<h2 align="center">Universidad de Guadalajara<br>Centro Universitario de Ciencias Exactas e Ingenierías<br>Departamento de Ciencias 
Alumno: Diaz Nava Adrian <br>
Código de alumno: 220793457 <br>
Carrera: Ingeniería Informática<br>
Proyecto: Tienda de libros (Leer & Leer)
<p>

## Requerimientos
* `PHP` >= 8.1
* `Jetstream`
* `MariaDB`
* `Node` >= v14.16.1
* `Bootstrap` = 5
* `Laravel Collective` = 6.x (Se puede agregar con: composer require laravelcollective/html)

## Instalación
1. Clonar el proyecto
    ```bash
    git clone https://github.com/Designerul/Caso_de_Estudio_-01.git
    cd Caso_de_Estudio
    ```
2. Instalar dependencias de PHP
    ```bash
    composer install
    ```
    Y también dependencias de JavaScript
    ```bash
    npm install && npm run buil
    ```

3. Crear archivo de configuración propio y generar llave
    ```bash
    copy .env.example .env
    php artisan key:generate
    ```

4. Configurar la base de datos en el archivo ``.env``

5. Ejecutar las migraciones y el seeder
    ```bash
    php artisan migrate --seed
    ```
