<div align="center">

# ⚡ Infinity Energy

### Landing page de producción para una empresa de soluciones de energía solar y almacenamiento en México.

Sitio corporativo **estático y en producción** (infinityenergy.com.mx) con video hero, tarjetas flip, carrusel infinito de partners y navegación responsive. Cero frameworks: HTML, CSS y JavaScript puros, optimizados para performance.

**[🚀 Sitio en vivo](https://infinityenergy.com.mx)**

![HTML](https://img.shields.io/badge/HTML5-black?logo=html5) ![CSS](https://img.shields.io/badge/CSS3-1572b6?logo=css3&logoColor=white) ![JS](https://img.shields.io/badge/JavaScript-f7df1e?logo=javascript&logoColor=black) ![Status](https://img.shields.io/badge/status-in--production-10b981)

</div>

---

## ✨ Características

| | |
|---|---|
| 🎬 **Hero con video** | Video en bucle como fondo para máximo impacto visual. |
| 🀄 **Tarjetas flip (3D)** | Soluciones (Time Shifting, Off-Grid, Híbrido) con efecto *flip* suave al hacer hover. |
| 🎠 **Carrusel infinito de partners** | Muestra marcas clave (Fronius, Sol-Ark, Enphase, Victron, Generac…) en loop sin interrupciones. |
| 📱 **Menú hamburguesa** | Sidebar móvil accesible (con `aria-expanded`) y navegación *scroll suave*. |
| 🎯 **Secciones comerciales** | Soluciones, Partners, Beneficios, Servicios, Quiénes Somos y Contacto. |
| ✨ **Animaciones de scroll** | Elementos con clase `reveal` aparecen al hacer scroll (Intersection Observer). |

---

## 🚀 Running

Como es un sitio fron-estático, basta con servir la carpeta:

```bash
# Con cualquier servidor estático (ej. python)
python3 -m http.server 8080
```

Abrí http://localhost:8080.

---

## 📁 Estructura

```
├── index.html      # Layout y secciones
├── styles.css      # Diseño, grid, animaciones y responsive
├── script.js       # Menú, flip cards, carrusel y reveals
├── CNAME           # infinityenergy.com.mx
└── imagenes/       # Íconos, fotos y logos de partners
```

---

## 📄 Licencia

Proyecto de uso privado. Consultá antes de redistribuirlo.