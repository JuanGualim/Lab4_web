# Lab4_web
# 🤖 Android Logo con HTML y CSS

Recreación del logo clásico de Android utilizando **únicamente HTML y CSS**, sin JavaScript y respetando el flujo normal del documento.

---

## 🧱 Tecnologías Utilizadas

- HTML5
- CSS3 moderno
- Flexbox como base principal del layout

No se utilizó:

- ❌ JavaScript  
- ❌ `position: absolute` para estructurar el layout  
- ❌ `float`  
- ❌ Generadores automáticos  

---


## 🧠 Conceptos Aplicados

### 🔹 Layout
- `display: flex` como base estructural
- Organización vertical y horizontal mediante flexbox
- Construcción completa dentro del flujo normal del documento

### 🔹 Selectores avanzados
- Selector descendiente (` `)
- Selector hijo directo (`>`)
- Selector adyacente (`+`)
- Selector general (`~`)
- `:first-child`
- `:last-child`
- `:nth-child()`
- `:has()`

### 🔹 Pseudo-elementos
- `::before`
- `::after`

### 🔹 CSS moderno
- Variables CSS (`--variable` y `var()`)
- `clamp()` para diseño adaptable
- CSS Nesting
- `@media` para responsividad
- Sistema de una sola variable para controlar todos los colores

---

## 🎨 Sistema de Color Dinámico

El diseño utiliza una variable base:

```css
:root {
  --base: #3ddc84;
}
