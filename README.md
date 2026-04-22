# 🌦️ Weather Frontend M3

Aplicación web que muestra el clima de distintas ciudades de Chile, con vista general y detalle de pronóstico.

---

## 📌 Descripción

Este proyecto corresponde al desarrollo de una aplicación web que permite visualizar el clima actual y el pronóstico semanal de distintas ciudades de Chile.

El usuario puede recorrer distintas localidades desde la página principal y acceder a una vista de detalle, donde se muestra información más completa como temperatura, estado del tiempo, humedad, viento y pronóstico para los próximos días.

---

## 🎯 Objetivo del proyecto

Refactorizar la aplicación desarrollada en el módulo anterior, enfocándome en:

- Mejorar la organización del código  
- Optimizar el diseño visual  
- Aplicar una metodología de estilos  
- Modularizar los estilos con SASS  
- Implementar un layout responsivo con Bootstrap  

---

## 🛠️ Tecnologías utilizadas

- HTML5 (estructura semántica)  
- CSS3 + SASS (SCSS)  
- Bootstrap 5  
- JavaScript (Vanilla JS)  
- LocalStorage  

---

## 🧩 Funcionalidades principales

- Visualización del clima actual de distintas ciudades  
- Cards dinámicas con:
  - Imagen de la ciudad  
  - Temperatura  
  - Estado del clima  
  - Icono representativo  
- Navegación a vista de detalle  
- Información detallada:
  - Temperatura actual  
  - Estado del clima  
  - Humedad  
  - Viento  
- Pronóstico semanal por ciudad  
- Navegación entre páginas  

---

## 🎨 Metodología de estilos (BEM)

Para los estilos utilicé la metodología **BEM (Block, Element, Modifier)**.

### Ejemplo:
place-card
place-card__title
place-card__button
place-card--sunny


Esto me ayudó a:

- Evitar conflictos entre estilos  
- Tener una estructura más clara  
- Reutilizar componentes  

---

## 🎯 Uso de SASS (SCSS)

En este proyecto utilicé **SASS (SCSS)** para organizar mejor los estilos y evitar tener todo en un solo archivo CSS.

Trabajé con el patrón **7-1**, separando los estilos en distintas carpetas según su función.

Además, utilicé `@use` para importar los archivos y centralizar todo en un archivo principal.

---

### 📁 Estructura SASS
scss/
├── abstracts/
│ ├── _variables.scss
│ └── _mixins.scss
│
├── base/
│ ├── _reset.scss
│ ├── _base.scss
│ └── _typography.scss
│
├── layout/
│ ├── _header.scss
│ ├── _main.scss
│ └── _footer.scss
│
├── components/
│ ├── _button.scss
│ ├── _card.scss
│ ├── _detalle.scss
│ ├── _hero.scss
│ └── _pronostico.scss
│
├── pages/
│ ├── _home.scss
│ └── _detalle-page.scss
│
├── themes/
│ └── (no utilizado en este proyecto)
│
├── vendors/
│ └── (no utilizado en este proyecto)
│
└── main.scss


---

### ⚠️ Sobre `themes` y `vendors`

Las carpetas `themes` y `vendors` las dejé creadas porque forman parte del patrón 7-1, pero en este proyecto no fue necesario utilizarlas.

- `themes`: se usa cuando hay distintos estilos (por ejemplo modo oscuro), lo cual no apliqué en este caso  
- `vendors`: se utiliza para librerías externas, pero Bootstrap lo trabajé mediante CDN  

Las dejé consideradas para futuros proyectos o mejoras.

---

### ⚙️ Cómo funciona

El archivo `main.scss` reúne todos los estilos y se compila automáticamente en:assets/css/main.css

Este archivo es el que finalmente se conecta con el HTML.

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
│ │
│ ├── js/
│ │ ├── data.js
│ │ ├── main.js
│ │ └── detalle.js
│ │
│ └── img/
│ ├── ciudades/
│ └── clima/

---

## 🔗 Enlace del repositorio

👉 https://github.com/Paula-front/weather-frontend-m3

---

## 👩‍💻 Autor

Paula Pérez Valenzuela  

---

## 📅 Año

2026  
