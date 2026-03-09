# PHYSICS — Centro de Estudios de Ingeniería

Plataforma web estática de tutorías de ingeniería para estudiantes de la EPN, USFQ y ESPOL en Ecuador.

## 🚀 Deployment en GitHub Pages

1. Subir todos los archivos a la raíz de la rama `main`
2. `Settings → Pages → Source: Deploy from branch: main / (root)`
3. URL: `https://[usuario].github.io/physics/`

## 📁 Estructura de Archivos

```
physics/
├── index.html              # Landing page principal
├── style.css               # CSS global unificado — NO duplicar estilos
├── PORTADA.jpg             # Imagen hero (reemplazar con imagen propia)
├── calculadora.html        # Integral definida (Simpson 1/3)
├── algebra-lineal.html     # Gauss-Jordan Ax=B
├── ecuaciones.html         # EDOs 2do orden (M-B-K / R-L-C)
├── metodos-numericos.html  # Newton-Raphson
├── estatica.html           # Caída libre con arrastre
├── circulo-mohr.html       # Círculo de Mohr 2D/3D
├── otto.html               # Ciclo Otto termodinámico
├── conduccion.html         # Conducción de calor en serie
├── probabilidad.html       # Distribuciones Normal/t/Chi²
└── README.md
```

## 🛠 Añadir una Nueva Herramienta

1. Copiar la estructura de cualquier herramienta existente
2. Mantener la navbar `.nav-physics` idéntica (definida en `style.css`)
3. Usar la sección `.tool-hero` para el encabezado
4. Añadir la tarjeta correspondiente en `index.html` (sección `#cursos`)
5. **No usar** `https://polyfill.io` — todos los navegadores modernos soportan ES6

## 🎨 Convenciones de Diseño

- **CSS**: Variables globales en `style.css`. Estilos de herramienta en `<style>` local
- **Fuentes**: Inter (UI) + Fira Code (código/valores numéricos) — cargadas desde Google Fonts
- **Colores**: Ver variables `:root` en `style.css`

## 📞 Contacto

WhatsApp: +593 995 324 419

© 2026 PHYSICS — Quito, Ecuador
