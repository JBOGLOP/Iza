# 🤍 Bienvenidos a nuestra casa en Iza

Guía de bienvenida digital para nuestra casa en **Iza, Boyacá** — Apto 201.

> Un espacio hecho con cariño, para compartir en familia, descansar y crear recuerdos bonitos.

📍 **Carrera 6 No. 3-88**, Iza · cerca al Hotel Casitas Barró

---

## 🌐 Ver la guía en línea

👉 **[https://JBOGLOP.github.io/bienvenidos-iza/](https://JBOGLOP.github.io/bienvenidos-iza/)**

> Reemplaza `bienvenidos-iza` por el nombre que le pongas al repositorio.

---

## ✨ Qué incluye

Esta guía está pensada para que nuestros invitados encuentren todo lo que necesitan durante su estadía:

- 📶 **Internet** — red y contraseña con un toque para copiar
- 🚨 **Alarma** — instrucciones para avisarnos al llegar y al salir
- 🏡 **Sobre la casa** — cocina, ropa de cama, lavadora, entretenimiento, plantas, frío y manejo de basuras
- 🌿 **Plantas** — un recordatorio dulce para regarlas
- 🍽️ **Recomendaciones gastronómicas** en Iza, Sogamoso y alrededores
- ♨️ **Termales** (Piscinas Erika, El Batán)
- 🧶 **Artesanías** (Rueca Izana, Tejidos Rebancá)
- 📍 **Botones directos a Google Maps** para cada lugar

---

## 🎨 Diseño

- **Paleta:** *Amaneceres de páramo* — cielo, lavanda suave, durazno claro y crema
- **Tipografías:** Cormorant Garamond (display) + Fraunces (cuerpo)
- **Sin dependencias externas** — solo HTML, CSS y un poquito de JavaScript
- **100% responsivo** — se ve bien en celular, tablet y escritorio
- Tarjetas plegables, animaciones suaves y un fondo con textura sutil

---

## 🚀 Cómo publicarlo en GitHub Pages

1. Sube `index.html` al repositorio (en la raíz)
2. Ve a **Settings → Pages**
3. En **Source**, elige la rama `main` (o `master`) y la carpeta `/ (root)`
4. Guarda y espera 1–2 minutos
5. Tu guía estará disponible en `https://JBOGLOP.github.io/[nombre-del-repo]/`

---

## 📂 Estructura del repositorio

```
bienvenidos-iza/
├── index.html          ← la guía completa
└── README.md           ← este archivo
```

Todo el CSS y JavaScript está embebido en `index.html`. Un solo archivo, sin compilación ni dependencias.

---

## 🛠️ Cómo personalizarlo

Para actualizar el contenido, edita directamente `index.html`:

- **WiFi:** busca el bloque `<div class="wifi-card">` y cambia red y contraseña
- **Recomendaciones:** cada lugar está en un bloque `<div class="recomendacion">`
- **Colores:** las variables CSS están al inicio del `<style>`, en `:root { ... }`

### Variables de color principales

```css
--cielo:#a8c4d8;       /* azul cielo de amanecer */
--lavanda:#b6a8c9;     /* lavanda de bruma */
--durazno:#e8b89a;     /* durazno suave */
--crema:#fbf6ec;       /* neblina */
--acento:#c97a52;      /* terracota acento */
--musgo:#8a9b6e;       /* verde campo */
```

---

## 📲 Compartir con invitados

Una vez publicada, comparte el link por WhatsApp:

```
🤍 Te dejo la guía completa para tu estadía en nuestra casa de Iza:
👉 https://JBOGLOP.github.io/bienvenidos-iza/

Ahí encontrarás el WiFi, recomendaciones de restaurantes y todo lo
que necesites. ¡Cualquier cosa nos escribes!
```

---

## 📝 Licencia

Uso personal. Este repositorio contiene información privada (dirección, WiFi) — manténlo público solo si lo deseas, o úsalo como repositorio privado y comparte el link directamente.

---

*Hecho con cariño desde Iza, Boyacá* ✨
