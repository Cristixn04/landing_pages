# 📂 Menú de Landing Pages

Este proyecto consiste en una página web simple que funciona como **menú de acceso a múltiples landing pages**.
Cada enlace muestra un **icono representativo** junto con el nombre de la página, permitiendo navegar fácilmente entre diferentes sitios o proyectos.

## 🚀 Características

* Menú visual con **15 enlaces a landing pages**
* Cada enlace incluye:

  * Un **icono**
  * Un **nombre descriptivo**
* Diseño organizado en **cuadrícula (grid)**
* Efecto **hover** para interacción visual
* Código simple usando **HTML y CSS**

## 🧱 Tecnologías utilizadas

* HTML5
* CSS3

## 📁 Estructura del proyecto

```
proyecto/
│
├── index.html
├── styles.css
│
└── iconos/
    ├── icono1.png
    ├── icono2.png
    ├── icono3.png
    ├── ...
    └── icono15.png
```

## ⚙️ Instalación y uso

1. Descarga o clona el repositorio.
2. Abre el archivo **index.html** en tu navegador.
3. Modifica los enlaces dentro del HTML para colocar las URLs de tus landing pages.

Ejemplo de enlace:

```html
<a href="https://tulanding.com" class="item">
    <img src="iconos/icono1.png" alt="Landing">
    <p>Nombre de la Landing</p>
</a>
```

## 🎨 Personalización

Puedes modificar fácilmente:

* **Cantidad de columnas** en el menú desde CSS:

```css
grid-template-columns: repeat(5, 1fr);
```

* **Tamaño de los iconos**
* **Colores del fondo**
* **Efectos de animación**

## 📱 Mejoras futuras

* Diseño responsive para móviles
* Animaciones más avanzadas
* Implementación con JavaScript para generar enlaces dinámicamente

## 📄 Licencia

Este proyecto es de uso libre para fines educativos o personales.


https://github.com/CondezPancake/GroupHTML-CSS-CPC.git