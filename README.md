# 🌦️ App del Clima de Ciudades de Chile

## 📌 Descripción

Este proyecto corresponde al desarrollo de una aplicación web que permite visualizar el clima actual y el pronóstico semanal de distintas ciudades de Chile.

El usuario puede explorar distintas localidades desde la página principal y acceder a una vista de detalle donde se muestra información más completa, incluyendo temperatura, estado del tiempo, humedad, viento y pronóstico de los próximos días.

---

## 🎯 Objetivo del proyecto

Refactorizar la aplicación desarrollada en el módulo anterior, enfocándose en:

- Organización de la interfaz
- Mejora del diseño visual
- Uso de metodología de estilos
- Modularización con SASS
- Implementación de layout responsivo con Bootstrap

---

## 🛠️ Tecnologías utilizadas

- **HTML5** (estructura semántica)
- **CSS3 + SASS (SCSS)** (estilos y modularización)
- **Bootstrap 5** (layout responsivo y componentes)
- **JavaScript (Vanilla JS)** (interacción y render dinámico)
- **LocalStorage** (persistencia de la ciudad seleccionada)

---

## 🧩 Funcionalidades principales

- Visualización del clima actual de distintas ciudades
- Cards dinámicas con:
  - Imagen de la ciudad
  - Temperatura
  - Estado del clima
  - Icono representativo
- Navegación a vista de detalle
- Visualización de:
  - Temperatura actual
  - Estado del clima
  - Humedad
  - Viento
- Pronóstico semanal por ciudad
- Navegación entre páginas

---

## 🎨 Metodología de estilos (BEM)

Se utilizó la metodología **BEM (Block, Element, Modifier)** para mantener un código CSS claro, escalable y fácil de mantener.

### Ejemplo:
place-card
place-card__title
place-card__button
place-card--sunny


Esto permite:

- Separar responsabilidades
- Evitar conflictos de estilos
- Mejorar la legibilidad del código

---

## 🎯 Uso de SASS (SCSS)

Se implementó SASS para modularizar los estilos mediante una estructura organizada basada en el patrón 7-1.

### Estructura utilizada:
scss/
├── abstracts/
│ ├── _variables.scss
│ └── _mixins.scss
├── base/
│ ├── _reset.scss
│ ├── _base.scss
│ └── _typography.scss
├── layout/
│ ├── _header.scss
│ ├── _main.scss
│ └── _footer.scss
├── components/
│ ├── _card.scss
│ ├── _detalle.scss
│ ├── _hero.scss
│ └── _pronostico.scss
├── pages/
│ ├── _home.scss
│ └── _detalle-page.scss
└── main.scss

El archivo `main.scss` centraliza todos los estilos y se compila automáticamente a:
assets/css/main.css


---

## 📂 Estructura del proyecto
weather-frontend-m3/
│
├── index.html
├── detalle.html
├── README.md
│
├── scss/
│ └── (estructura SASS)
│
├── assets/
│ ├── css/
│ │ └── main.css
│ ├── js/
│ │ ├── data.js
│ │ ├── main.js
│ │ └── detalle.js
│ └── img/
│ ├── ciudades/
│ └── clima/


---

## 🔗 Enlace del repositorio

👉(https://github.com/Paula-front/weather-frontend-m3)

---

## 👩‍💻 Autor

**Paula Pérez Valenzuela**

---

## 📅 Año

2026