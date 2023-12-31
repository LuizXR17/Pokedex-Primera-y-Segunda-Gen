
# Pokedex
Este proyecto es una Pokedex simple que muestra los primeros 251 Pokémon utilizando la [PokeAPI](https://pokeapi.co) como fuente de datos.






## Características

- Muestra una lista de los primeros 251 Pokémon con sus imágenes correspondientes.
- Al hacer clic en un Pokémon, se muestra su variante Shiny (brillante).
- Muestra habilidades y tipos de los 251 pokemons
- Buscar Pokemon por tipo: Puedes buscar Pokemon por su tipo en la barra de búsqueda.   Solo tienes que escribir el tipo de Pokemon (por ejemplo, "fuego", "agua", etc.) y la Pokedex mostrará todos los Pokemon de ese tipo.
- Al hacer clic nuevamente en el Pokémon, se vuelve a su imagen original.
- Diseño de barra de búsqueda mejorado: La barra de búsqueda tiene un diseño mejorado  que se expande cuando haces clic en ella y se contrae cuando no está en uso.
- Mostrar altura y peso: Ahora cada tarjeta de Pokémon muestra la altura en centímetros y el peso en kilogramos del Pokémon.
- Mostrar ataque, defensa y velocidad: Cada tarjeta de Pokémon ahora también muestra el ataque, la defensa y la velocidad del Pokémon.
- Descripción de Pokemon: Cada tarjeta de Pokémon ahora incluye una descripción del Pokémon.
- Comparar Pokémon: Los usuarios pueden añadir Pokémon a una lista de comparación y ver sus detalles lado a lado.

## Código corregido

Este proyecto ha sido corregido y mejorado. Aquí están los cambios más recientes:
- Barra de búsqueda mejorada
- Capacidad para buscar Pokémon por tipo
- Mostrar más detalles sobre cada Pokémon
- Se añadió la descripción de cada Pokemon a las tarjetas.
- Se ajustó la altura de las tarjetas para que todas tengan la misma altura, independientemente de la longitud de la descripción.
- Se redujo la altura mínima de las tarjetas para hacerlas un poco más pequeñas.
- Se añadió una verificación para asegurarse de que los usuarios no puedan comparar Pokémon sin añadir primero algún Pokémon a la lista de comparación. Si un usuario intenta comparar sin añadir un Pokémon, se mostrará una alerta de error.
- Se añadió una alerta de éxito que se muestra cuando un Pokémon se añade a la lista de comparación.
- Se ajustó la posición de la alerta de éxito para que se muestre en el centro de la pantalla.


## Instalación

Para instalar y ejecutar este proyecto, primero clona el repositorio, luego abre el archivo `index.html` en tu navegador.

## Dependencias

Este proyecto utiliza la biblioteca SweetAlert2 para mostrar alertas. Puedes incluirlo en tu proyecto a través de un CDN o instalándolo a través de npm.

## Cómo empezar

Si te interesa este proyecto y quieres tenerlo en tu máquina local para desarrollo y pruebas, puedes clonarlo directamente desde GitHub.

Sigue estos pasos:

1. En GitHub, navega hasta la página principal del repositorio.
2. Sobre la lista de archivos, haz clic en el botón verde "Code".
3. Para clonar el repositorio usando HTTPS, debajo de "Clonar con HTTPS", haz clic en el icono de copiar al portapapeles. Para clonar el repositorio usando una llave SSH o GitHub CLI, haz clic en "Use SSH" o "Use GitHub CLI", luego haz clic en el icono de copiar al portapapeles.
4. Abre Git Bash.
5. Cambia el directorio de trabajo actual a la ubicación donde quieres clonar el directorio.
6. Escribe `git clone`, y luego pega la URL que copiaste antes.
7. Presiona Enter para crear tu clon local.

```bash
$ git clone https://github.com/LuizXR17/Pokedex-Primera-y-Segunda-Gen
```
8. Navega hasta el directorio del proyecto y abre el archivo index.html en tu navegador para ver la Pokedex en acción.

## Contribuir

Las contribuciones son bienvenidas. Por favor, abre un issue o un pull request para sugerir cambios o mejoras.

## Tecnologías Utilizadas
-  ![HTML logo](https://upload.wikimedia.org/wikipedia/commons/thumb/8/80/HTML5_logo_resized.svg/120px-HTML5_logo_resized.svg.png)
-  ![CSS logo](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/CSS3_logo_and_wordmark.svg/120px-CSS3_logo_and_wordmark.svg.png)
- ![JavaScript logo](https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unofficial_JavaScript_logo_2.svg/120px-Unofficial_JavaScript_logo_2.svg.png)
- ![PokeAPI logo](data:image/png;base64,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)

## Autor

- [@Kaizen](https://github.com/LuizXR17)


![Logo](https://i.imgur.com/BtDH18Q.png[/img])