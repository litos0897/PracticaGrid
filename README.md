# PGrid - Portfolio Personal

## 👤 Autor
**Carlos Sánchez Criado** (1º DAM)

---

## 📝 Descripción de la práctica
Este proyecto consiste en una página web personal del tipo presentación interactiva. La estructura visual está organizada principalmente mediante un sistema de cuadrícula que distribuye la información en diferentes tarjetas (*cards*).

El diseño está enfocado en destacar la identidad, visión y proyectos del autor, incluyendo:
* Una sección de biografía y filosofía personal.
* Un apartado de **Intereses** (Automovilismo, DJ, Fotografía).
* La sección **Laboratorio**, que expone un proyecto destacado ("Hundir la flota" desarrollado en Java) con un enlace directo a su repositorio.
* Un diseño web adaptable (*Responsive Web Design*) que garantiza la correcta visualización en dispositivos de escritorio, tablets y teléfonos móviles.
* Efectos interactivos (*hover*) en las tarjetas y botones para mejorar la experiencia de usuario.

---

## 🛠️ Tecnologías utilizadas
* **HTML5:** Para el maquetado semántico y la estructura del contenido.
* **CSS3:** Para los estilos, animaciones y el diseño visual de la página. Se ha implementado de forma específica:
    * **CSS Grid:** Para la estructura principal de la cuadrícula en la versión de escritorio.
    * **Flexbox:** Para la alineación interna de elementos específicos (como la cabecera y la sección del laboratorio).
    * **Variables CSS (`:root`):** Para mantener una paleta de colores coherente y facilitar el mantenimiento (ej. `--accent-purple`, `--bg-body`).
    * **Anidamiento CSS (*Nesting*):** Para organizar de forma más limpia los selectores dependientes y estados como `:hover`.
    * **Media Queries (`@media`):** Para la adaptabilidad a diferentes pantallas
