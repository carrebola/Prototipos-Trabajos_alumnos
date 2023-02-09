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

## Historia 1 - Prototipos
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
  
  

