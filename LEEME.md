# 🥟 Sabores de Chile — Página de inicio

Proyecto de la página de inicio de un sitio web, construido con la estructura de
**WordPress + Elementor + Royal Addons**.

> **La idea:** un sitio sencillo sobre **cocina tradicional chilena**. Comunica de
> qué trata (rescatar y compartir recetas de toda la vida) y qué contenidos ofrece
> (recetas paso a paso + historia y tradiciones de la comida chilena).

---

## 📁 Qué hay en esta carpeta

```
sabores-de-chile/
├── index.html              ← la página de inicio (ábrela en el navegador)
├── css/
│   └── estilos.css         ← estilos del sitio
├── plantilla-elementor.json← plantilla para IMPORTAR en Elementor (opcional)
└── LEEME.md                ← este archivo
```

Para verla: haz **doble clic en `index.html`** y se abre en tu navegador. No
necesita internet (solo las tipografías de Google se cargan en línea; si no hay
conexión, usa fuentes del sistema).

---

## ✅ Cómo cumple cada instrucción del trabajo

| Instrucción | Dónde está en la página |
|---|---|
| Al menos **3 secciones temáticas** | 1) **Bienvenida** (hero), 2) **Recetas tradicionales**, 3) **Historia y tradiciones** (+ una extra "Sobre el sitio") |
| Una sección de **bienvenida / presentación** | Sección "Sabores de Chile" con título, texto y botón |
| Dos secciones que **anticipan los contenidos** | "Recetas tradicionales" y "Historia y tradiciones" |
| Cada sección con **título (widget de encabezado)** | Widgets *Heading* de Elementor y *Advanced Heading* de Royal Addons |
| Cada sección con **bloque de texto descriptivo** | Widgets *Text Editor* de Elementor |
| Al menos **un elemento visual** | ✔ Imágenes/ilustraciones (empanada y uvas), ✔ íconos en las tarjetas, ✔ separador decorativo |
| **Menú de navegación** | Menú superior: Inicio · Recetas · Tradiciones · Sobre el sitio |

### Widgets usados (Elementor vs Royal Addons)
- **Elementor (core):** Heading, Text Editor, Image, Divider (separador).
- **Royal Addons (`wpr-`):** Advanced Heading (título del hero), Button (botón
  "Ver las recetas") e Icon Box (las 3 tarjetas de recetas).

---

## 🌐 Cómo conseguir la URL para entregar

El trabajo pide **entregar una URL**. Tienes dos caminos:

### Opción A — Hacerlo en WordPress de verdad (lo que pide el ramo)
Usa esta carpeta como **guía/maqueta** y reconstruye la página en tu WordPress:

1. **Crea una página nueva:** Escritorio → *Páginas → Añadir nueva*. Título: `Inicio`.
2. **Edita con Elementor:** botón *Editar con Elementor*.
3. **Sección de bienvenida:** agrega una sección de 2 columnas → en la izquierda
   pon *Advanced Heading* (Royal) con "Sabores de Chile", un *Text Editor* con la
   intro y un *Button* (Royal) "Ver las recetas"; en la derecha una *Imagen*.
4. **Separador:** arrastra el widget *Divisor (Divider)*.
5. **Sección Recetas:** una fila con *Heading* + *Text Editor*, y debajo 3 columnas
   con *Icon Box* (Royal): empanadas, pastel de choclo y cazuela.
6. **Sección Tradiciones:** 2 columnas → imagen + (*Heading* y *Text Editor*).
7. **Publica:** botón verde *Publicar* (¡no lo dejes en borrador!).
8. **Agrégala al menú:** Escritorio → *Apariencia → Menús* → marca la página
   "Inicio" → *Añadir al menú* → *Guardar menú*.
9. La **URL** es la dirección que muestra el navegador al ver la página
   (por ejemplo `https://tu-sitio.com/` o `https://tu-sitio.com/inicio`). Esa es
   la que entregas.

> 💡 Para ir más rápido puedes **importar** `plantilla-elementor.json`:
> en Elementor abre el menú ☰ → *Plantillas guardadas* → *Importar plantillas* →
> elige el archivo. Luego *Insertar* la plantilla en tu página. (Funciona con los
> widgets base de Elementor; los de Royal Addons los agregas como en los pasos.)

### Opción B — Publicar esta carpeta tal cual (rápido, para tener una URL ya)
Si necesitas una URL en minutos sin instalar WordPress:
- Entra a **app.netlify.com/drop** y **arrastra la carpeta `sabores-de-chile`**.
  Te entrega una URL pública al instante.
- O sube la carpeta a un repositorio y activa **GitHub Pages**.

---

## 🎨 Sobre el diseño
Colores cálidos (rojo de empanada/vino, dorado de la masa, crema) y dos tipografías
de Google Fonts: *Playfair Display* para títulos y *Poppins* para los textos.
La idea fue que se viera apetecible pero simple, como un primer proyecto.

¡Buen provecho! 🇨🇱
