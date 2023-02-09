# FrontEnd Sprint 1
***
## Tabla de contenidos

1. [Creamos el proyecto](#creamos-proyecto)
2. [Item 2](#item2)()

## Tecnologías empleadas

 [![vite](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQsTYQgDwKWbIEM8WQ76zl_Oaw16RHcn8_J0Q&usqp=CAU)](https://www.npmjs.com/package/vite)

## Recursos
- [Crear el archivo readme.md](https://www.ionos.es/digitalguide/paginas-web/desarrollo-web/archivo-readme/)
- [Versionado con git](https://www.youtube.com/watch?v=1B9iP611WUY&list=PLY1J8ju7Eq-TUBGmySQNivh2F1Yq0CgQj&index=18)
- [Git flow básico](https://www.youtube.com/watch?v=CTM-pvIZk48)
 
 # Inicio del proyecto
 ## Creamos el proyecto
- Creamos carpeta con nombre proyecto. La abrimos con vscode y abrimos un terminal.
- Creamos el proyecto con vite: (el punto es para que cree el proyecto en la carpeta en la que estamos ubicados con vscode)
   
    ```
    $ npm create vite .
    ```
  
- Instalamos las dependencias y abrimos un servidor de prueba
 
    ```
    $ npm install
    $ npm run dev
    ```
- Modificamos el título del proyecto y verificamos que todo está en orden


![](public/recortes/comenzamos.png)

- Creamos repositorio en git y enlazamos con nuestra cuenta de github. Lo haremos mediante las herramientas de vscode.
- Ahora tenemos una rama *master* con el proyecto básico. Vamos a crear una rama de desarrollo *dev* a partir de la rama *master*
- Y creamos el primer commit de desarrollo: 'Comenzamos a desarrollar'


# Sprint 2: Prototipos html 
## Historia 1 - Prototipos
- Creamos una rama **'prototipos'** a partir de la rama **dev** para desarrollar los prototipos en html.
- Para cada prototipo terminado crearemos un commit especifico sobre el repositorio
### Bootstrap y Bootswatch
- Crearmos una carpeta con los prototipos en html que construimos a partir de nuestros bocetos/mockups
- Creamos los archivos html. Por el momento creamos estructuras de trabajo con clases de bootstrap desde cdn usando un theme especifico desde la web [Bootswatch](https://bootswatch.com/) 
- Para los iconos usaremos [feather ](https://feathericons.com/)

```
<!-- Bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css
    ">
    <!-- Boostswatch -->
    <link href="
https://cdn.jsdelivr.net/npm/bootswatch@5.2.3/dist/superhero/bootstrap.min.css
" rel="stylesheet">
    <!-- Iconos -->
    <script src="https://unpkg.com/feather-icons"></script>
```
### Header
- Para el header crearmos una barra de navegación que permanecerá siempre enganchada en la parte superior.
- Añadimos el logo y un icono para gestionar el menú de usuario
  ```commit navbar 1.0```

### Prototipos
- Creamos las páginas home, registro, login, admin

### Pull requests sobre dev
Cuando hemos terminado esta primera historia creamos un pull request de esta historia sobre la rama dev.
La gráfica de git debería quedar algo así:

# Sprint 3: Validación de formularios desde cliente
- Definirmos las reglas para cada campo de formulario (tipo, requerido, patrón con expresión regular, etc)
- Actualizamos los formularios html para validación utilizando bootstrap
- Creamos las funciones js para la validación de cada formulario
- Creamos un commit para cada página

## Login
- En el form simplemente comprobamos que los campos email y password se han completado y que email tiene forma de email
- creamos el script que detecta el submit y aplicamos validación con boostrap. Dejamos el submit pendiente de ejecutar (mostramos mensaje por consola)

**Commit: página_login_validacion_v1**
## Registro
- Idem que login pero con reglas más extrictas: 
  - Requerimos todos los campos
  - email correcto
  - la contraseña tiene una expresión regular básica que cumple que debe ser más de 8 caracteres y que pueden ser letras mayusculas o minusculas

**Commit: página_registro_validacion_v1**

## EditarPerfil
- Las mismas reglas que para el registro

**Commit: página_editarPerfil_validacion_v1**

  

