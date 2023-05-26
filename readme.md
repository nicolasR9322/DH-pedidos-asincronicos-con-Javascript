Trabajo práctico de Digital House donde se consumiran APIS desde el front-end


descripcion: El objetivo será practicar cómo consumir una API Rest de manera
asíncrona desde el front-end usando fetch API

    -base:
        -carpeta front-end proporcionada
        -carpeta back-end proporcionada junto con instalacion de dependencias asociadas

    desafio 1 :
        -en el proyecto front-end
            -listar todas las peliculas en el home.html que nos trae
            -en formularios cargar datos de una pelicula en particular para luego poder modificarla o eliminarla
                -detalle de una pelicula : a traves de la ruta de api router.get('/:id', moviesAPIController.detail)
                -modificar  una pelicula a traves de la ruta : router.put('/update/:id', moviesAPIController.update);
            -utilizar el formulario para poder crear una pelicula por medio del endpoint router.post('/create', moviesAPIController.create);
            -utilizar el formulario para borrar una pelicula a traves de un endpoint
            