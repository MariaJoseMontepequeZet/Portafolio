# 💻 Portafolio Web · María José Montepeque Zet

Sitio web personal para presentar mi trayectoria académica, habilidades técnicas y proyectos en las áreas de **Ingeniería en Ciencias y Sistemas** y **Ciberseguridad**.

> Hecho por **María José Montepeque Zet** ✨

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Licencia MIT](https://img.shields.io/badge/Licencia-MIT-7e076e?style=flat)

---

## 📋 Tabla de contenido

- [📍 Introducción](#-introducción)
- [🔍 Secciones del sitio](#-secciones-del-sitio)
- [🛠️ Tecnologías](#️-tecnologías)
- [⚙️ Cómo ejecutarlo](#️-cómo-ejecutarlo)
- [📂 Estructura del proyecto](#-estructura-del-proyecto)
- [🎨 Sistema de estilos](#-sistema-de-estilos)
- [🌿 Flujo de trabajo](#-flujo-de-trabajo)
- [📄 Licencia](#-licencia)

---

## 📍 Introducción

Portafolio estático construido con HTML y CSS puros, sin frameworks ni dependencias. Centraliza mi perfil como estudiante de la **USAC**, mis certificaciones en **Ciberseguridad**, **Python** e **Inteligencia Artificial**, y mis proyectos de desarrollo.

```markdown
> [!NOTE]
> Tema oscuro con acentos violeta y magenta, pensado para destacar las ilustraciones y transmitir una identidad profesional orientada al sector tecnológico.

---

## 🔍 Secciones del sitio

| Página | Contenido |
|---|---|
| **Inicio** | Presentación, perfil aspiracional y descripción personal en tarjetas con borde neón animado. |
| **Sobre mí** | Cuatro tarjetas *flip* con quién soy, gustos, formación e intereses IT. |
| **Habilidades** | Cuadrícula de competencias técnicas y herramientas; cada tarjeta despliega su descripción. |
| **Proyectos** | Listado de proyectos con etiquetas de tecnologías y enlace a cada repositorio. |
| **Contacto** | Enlaces a LinkedIn, GitHub y correo. |

**Características:**
- 🌑 Tema oscuro con acentos violeta y tipografías Inter / Space Grotesk.
- 📱 Diseño responsivo con menú hamburguesa sin JavaScript.
- ♿ Enlace "saltar al contenido", `aria-current`, foco visible y `prefers-reduced-motion`.
- 🧩 Sistema de componentes reutilizables: `.tarjeta`, `.btn`, `.chip`, `.etiqueta`.
- 🖼️ Iconos SVG inline y favicon vectorial (sin peticiones extra).

---

## 🛠️ Tecnologías

- **HTML5** — estructura semántica (`main`, `article`, `nav`, `footer`).
- **CSS3** — variables personalizadas, Flexbox, Grid, transformaciones 3D y animaciones.
- **Google Fonts** — Poppins y Quicksand.
- **SVG** — cursores e iconografía vectorial.
- **Google Fonts** — Inter y Space Grotesk.

---

## 🎨 Sistema de estilos

Cada página carga `CSS/base.css` más su hoja específica. Los tokens se definen una sola vez en `:root`:

```css
:root {
    --fondo: #0b0a14;
    --superficie: #141221;
    --primario: #b06cff;
    --acento: #ff4fd8;
    --texto: #f3f1ff;
    --texto-suave: #a9a4c2;
    --fuente-titulos: 'Space Grotesk', sans-serif;
    --fuente-cuerpo: 'Inter', sans-serif;
}

---

## ⚙️ Cómo ejecutarlo

**Requisitos:** un navegador moderno. Para editar, se recomienda Visual Studio Code.

1. Clona el repositorio:
   ```bash
   git clone https://github.com/MariaJoseMontepequeZet/Portafolio.git
   cd Portafolio