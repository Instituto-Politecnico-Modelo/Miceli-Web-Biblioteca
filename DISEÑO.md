# Biblioteca Popular Pueyrredón Norte — Diseño Web

---

## Identidad del lugar

- Biblioteca comunitaria con más de 100 años de historia
- Ubicada en Villa Pueyrredón, Buenos Aires
- Edificio de arquitectura neocolonial
- Vibra: cálida, histórica, popular y comunitaria

---

## Paleta de colores

| Rol | Nombre | HEX |
|---|---|---|
| Principal | Crema Pergamino | `#EDE0C4` |
| Secundario | Verde Colonial | `#4D6B45` |
| Acento (botones CTA) | Terracota | `#C1541A` |

---

## Tipografía

| Rol | Fuente | Google Fonts |
|---|---|---|
| Títulos | **Playfair Display** | [Ver](https://fonts.google.com/specimen/Playfair+Display) |
| Cuerpo | **Source Sans 3** | [Ver](https://fonts.google.com/specimen/Source+Sans+3) |

---

## Archivos de diseño

| Archivo | Descripción |
|---|---|
| [wireframe_biblioteca_pueyrredon_norte.html](wireframe_biblioteca_pueyrredon_norte.html) | Boceto en escala de grises · SVG · 7 secciones |
| [mockup_biblioteca_pueyrredon_norte.html](mockup_biblioteca_pueyrredon_norte.html) | Mockup a color · HTML5 completo · paleta + tipografías aplicadas |

---

## Estructura de la página

| # | Sección | Fondo |
|---|---|---|
| 1 | Navbar (sticky) | Crema `#EDE0C4` |
| 2 | Hero | Ilustración SVG neocolonial con overlay |
| 3 | Sobre Nosotros | Crema oscura `#f6efe0` |
| 4 | Servicios | Crema `#EDE0C4` |
| 5 | Novedades y Agenda | Crema oscura `#f6efe0` |
| 6 | Contacto | Crema `#EDE0C4` |
| 7 | Footer | Verde Colonial `#4D6B45` |

---

## Secciones / Contenido

- **Navbar:** Logo + nombre, links a las 5 secciones principales. Link activo subrayado en terracota.
- **Hero:** Ilustración SVG del edificio neocolonial, eyebrow "Villa Pueyrredón · desde 1916", H1, botón CTA principal.
- **Sobre Nosotros:** Texto descriptivo + ilustración SVG del edificio. Mención a "la Casita de Tucumán".
- **Servicios:** 4 cards — Préstamo, Sala de Lectura, Talleres, Actividades Culturales.
- **Novedades y Agenda:** 3 cards con fecha, título, descripción y etiqueta (libre/cupos/permanente).
- **Contacto:** Dirección, teléfono y horarios en cards. Botón CTA `mailto:`.
- **Footer:** Columna institucional, dirección, horarios, redes sociales. Línea de copyright.

---

## Notas y decisiones de diseño

- El mockup es un archivo HTML5 standalone (con `<!DOCTYPE html>`) — se puede abrir directamente en el navegador.
- Los colores están definidos como CSS custom properties (variables) en `:root` para facilitar cambios globales.
- Los íconos usan [Tabler Icons](https://tabler.io/icons) (webfont via CDN).
- El navbar es `position: sticky` para que permanezca visible al hacer scroll.
- La ilustración del hero es SVG inline — no depende de imágenes externas.
- Tipografías cargadas desde Google Fonts: Playfair Display + Source Sans 3.
