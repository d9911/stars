[English](README.md) | Español | [Русский](README.ru.md)

# Star Rating

Una interfaz de navegador accesible para seleccionar y mostrar una valoración de una a cinco estrellas.

## Dirección web

[stars.d9911.org](https://stars.d9911.org/)

## Funciones

- Selecciona una valoración de una a cinco mediante botones de estrellas o un control de selección.
- Actualiza las estrellas activas, la salida de valoración en vivo y el estado accesible de los botones.
- Previsualiza una valoración al pasar el puntero y descarga la valoración actual como archivo SVG.
- Ofrece temas claro y oscuro y traducciones de interfaz en inglés, español y ruso.

## Uso

1. Selecciona una valoración con los botones de estrellas o el desplegable.
2. Revisa la salida de texto actualizada y las estrellas visuales.
3. Elige **Descargar SVG** para guardar el gráfico de valoración actual.

## Ejecución local

Es un sitio estático. Desde la raíz del repositorio, sirve los archivos con cualquier servidor HTTP estático; por ejemplo:

```bash
python3 -m http.server 8000
```

Después abre [http://localhost:8000](http://localhost:8000).

## Estructura

```text
index.html              marcado de la aplicación y lógica de interacción
theme.css               estilos de tema de la interfaz
assets/                 iconos
manifest.webmanifest    manifiesto de aplicación web
```

## Tecnologías

HTML, CSS, JavaScript, SVG y Web Storage API.

## Licencia

Los términos de distribución se indican en [LICENSE](LICENSE).

## Autor

Denis Gutsuliak ([d9911.org](https://d9911.org/)).
