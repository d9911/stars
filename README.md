# en

Star Rating Component

This project is a simple star rating component created with HTML, CSS, and JavaScript. It allows users to dynamically select and display a star rating from 1 to 5 stars.
Features

Displays 5 stars by default.
Dynamically updates the number of active stars based on user selection.
Uses a dropdown (<select>) to choose the rating.
Easy to integrate into any web project.
Installation

Copy the HTML, CSS, and JavaScript into your project.
Ensure the styles are included for proper star rendering.
Use the component in any part of your webpage.
Usage

Example:

The updateStars() function is used to set the number of active stars, and ratingSelector is the dropdown menu that allows users to select from 1 to 5 stars.
Project Structure

# es

Componente de Calificación de Estrellas

Este proyecto es un componente de calificación de estrellas simple creado con HTML, CSS y JavaScript. Permite a los usuarios seleccionar y mostrar dinámicamente una calificación de 1 a 5 estrellas.
Características

Muestra 5 estrellas por defecto.
Actualiza dinámicamente el número de estrellas activas según la selección del usuario.
Utiliza un menú desplegable (<select>) para elegir la calificación.
Fácil de integrar en cualquier proyecto web.
Instalación

Copia el HTML, CSS y JavaScript en tu proyecto.
Asegúrate de que los estilos estén incluidos para la representación correcta de las estrellas.
Usa el componente en cualquier parte de tu página web.
Uso

Ejemplo:

La función updateStars() se utiliza para establecer el número de estrellas activas, y ratingSelector es el menú desplegable que permite a los usuarios seleccionar de 1 a 5 estrellas.
Estructura del Proyecto

# ru

# Star Rating Component

Это простой компонент для динамического отображения звёзд (рейтинга) с возможностью выбора количества звёзд. Компонент написан на чистом HTML, CSS и JavaScript, и его можно легко интегрировать в любой проект.

## Функциональность

- Отображает 5 звёзд.
- Активирует определённое количество звёзд на основе значения, выбранного пользователем.
- Селектор для выбора от 1 до 5 звёзд.

## Установка

1. Скопируйте HTML, CSS и JS код в нужный файл проекта.
2. Убедитесь, что подключили стили для корректного отображения звёзд.
3. Используйте компонент в любом месте на странице.

## Использование

Этот компонент использует селектор для выбора количества звёзд, и динамически отображает активные звёзды на основе выбранного значения.

### Пример использования:

```html
<div class="stars" id="stars">
	<!-- звёзды будут автоматически обновляться в зависимости от выбранного значения -->
</div>

<select id="ratingSelector">
	<option value="1">1 звезда</option>
	<option value="2">2 звезды</option>
	<option value="3">3 звезды</option>
	<option value="4">4 звезды</option>
	<option value="5">5 звёзд</option>
</select>
```

JavaScript логика:
Функция updateStars(rating) обновляет активные звёзды на основе выбранного рейтинга.
Селектор ratingSelector используется для выбора количества звёзд от 1 до 5.
Структура проекта

```yaml
project/
│
├── index.html    # Главный файл HTML с компонентом звёздного рейтинга
├── styles.css    # Стили для звёзд и селектора
└── app.js        # JavaScript для динамического обновления звёзд
```


## Лицензия
Этот проект лицензирован по GPL-3.0 — см. файл [LICENSE](LICENSE) для деталей.