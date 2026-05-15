# Mundial 2026 — Landing Page

## 📁 Estructura del proyecto

```
mundial-landing/
├── index.html              ← Archivo principal (ábrelo en el navegador)
├── README.md
├── css/
│   └── styles.css          ← Todos los estilos
└── images/
    ├── estadio-azteca.jpg  ← Imagen del Estadio Azteca (CDMX)
    ├── estadio-akron.jpg   ← Imagen del Estadio Akron (Guadalajara)
    └── estadio-bbva.jpg    ← Imagen del Estadio BBVA (Monterrey)
```

---

## 🖼️ Imágenes de los estadios

Guarda las 3 imágenes en la carpeta **`images/`** con estos nombres exactos:

| Estadio                       | Ciudad         | Nombre del archivo      |
|-------------------------------|----------------|-------------------------|
| Estadio Azteca                | Ciudad de México | `estadio-azteca.jpg`  |
| Estadio Akron (Chivas)        | Guadalajara    | `estadio-akron.jpg`     |
| Estadio BBVA (Gigante de Acero) | Monterrey    | `estadio-bbva.jpg`      |

**Recomendaciones:**
- Tamaño ideal: **1200 × 800 px** (proporción horizontal)
- Formato: `.jpg` (si las tienes en `.png` o `.webp`, cámbiales la extensión o el nombre dentro del HTML)
- Peso recomendado: menos de 300 KB cada una para que cargue rápido

---

## 🎬 Videos de YouTube

Tienes que pegar **3 IDs de video** dentro de `index.html`. Busca los comentarios marcados con ✏️.

### Cómo obtener el ID de un video de YouTube

Si la URL del video es:
```
https://www.youtube.com/watch?v=dQw4w9WgXcQ
```
El ID es la parte después de `v=`, es decir: `dQw4w9WgXcQ`

### Dónde pegar cada ID

Abre `index.html`, busca la sección `<!-- ============ VIDEOS ============ -->` y reemplaza:

```html
src="https://www.youtube.com/embed/PEGAR_ID_VIDEO_1"
src="https://www.youtube.com/embed/PEGAR_ID_VIDEO_2"
src="https://www.youtube.com/embed/PEGAR_ID_VIDEO_3"
```

Por ejemplo, quedaría así:
```html
src="https://www.youtube.com/embed/dQw4w9WgXcQ"
```

---

## 🚀 Cómo desplegar

### Opción 1: Abrir localmente
Solo haz doble clic en `index.html` y se abrirá en tu navegador.

### Opción 2: GitHub Pages (gratis)
1. Sube la carpeta `mundial-landing/` a un repositorio de GitHub.
2. En el repo → Settings → Pages → Source: `main` branch / root.
3. Tu sitio estará en `https://tu-usuario.github.io/nombre-repo/`.

### Opción 3: Netlify / Vercel (gratis, drag & drop)
1. Entra a [netlify.com/drop](https://app.netlify.com/drop) o [vercel.com](https://vercel.com).
2. Arrastra la carpeta `mundial-landing/` completa.
3. Listo, tendrás una URL pública.

---

Hecho con pasión por **Marian** ⚽
