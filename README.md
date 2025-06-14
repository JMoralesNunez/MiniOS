# MiniOS

MiniOS es un prototipo de sistema operativo web ficticio, construido únicamente con HTML y CSS, sin usar JavaScript. El objetivo es simular una interfaz de sistema operativo simple, donde se pueden abrir y cerrar "aplicaciones" básicas desde un menú lateral o inferior (según el tamaño de la pantalla).

## Contenido del Proyecto

Este proyecto tiene dos archivos principales:

- `index.html`  
  Estructura principal del sistema, con un menú de navegación, secciones para mostrar las aplicaciones y botones para cerrarlas.

- `main.css`  
  Estilos visuales del sistema: diseño responsivo, colores, posición del menú, comportamiento de las "ventanas" de aplicaciones, etc.

## Cómo funciona

- Al abrir el archivo `index.html` en un navegador, verás una barra de navegación con tres opciones:
  - Notas
  - Tareas
  - Clima

- Al hacer clic en cualquiera de ellas, se abre una "ventana" con la aplicación correspondiente cargada dentro de un iframe.

- Dentro de cada aplicación, hay una barra superior con un botón de cierre (una "X"). Al hacer clic en esta "X", la ventana se cierra.

- Puedes volver a abrir cualquier aplicación desde la barra de navegación.

## Diseño adaptable (Responsive)

El sistema se adapta según el tamaño de la pantalla:

- En pantallas grandes, el menú aparece en una barra vertical a la izquierda.
- En pantallas pequeñas (como celulares), el menú aparece en la parte inferior.

## Archivos adicionales esperados

Las aplicaciones se cargan desde archivos externos dentro de la carpeta `/applications/`:

- `notes.html`
- `homeworks.html`
- `weather.html`

(Estos archivos deben existir y contener el contenido de cada app).

## Cómo usar

1. Descarga o clona el repositorio.
2. Asegúrate de tener los archivos HTML de las aplicaciones dentro de `/applications/`.
3. Abre `index.html` en tu navegador.
4. Navega entre las aplicaciones desde el menú y ciérralas con el botón "X".


