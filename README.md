# Maderas Aurora — Sitio web

Sitio web estático de una mueblería ficticia, desarrollado con HTML5 y CSS3. Presenta productos de madera, contenido multimedia y un mapa de ubicación.

## Tecnologías utilizadas
- HTML5 para la estructura semántica.
- CSS3 para el diseño adaptable y las animaciones.
- Audio MP3 y video MP4 integrados mediante etiquetas HTML.
- OpenStreetMap para el mapa insertado.

## Estructura del proyecto
```text
muebleria/
├── index.html
├── README.md
├── css/
│   └── style.css
├── imagenes/
│   ├── mesacedro.jpg
│   ├── sillanogal.jpg
│   └── sofaroble.jpg
└── recursos/
    ├── carpintero.mp3
    └── carpintero.mp4
```

## SEO básico implementado
- Etiqueta `title` descriptiva.
- Metadatos `description`, `keywords`, `viewport`, `robots` y `author`.
- Atributos `alt` descriptivos en todas las imágenes.
- Títulos y secciones semánticas (`header`, `nav`, `main`, `section`, `footer`).
- Metadatos Open Graph básicos.

## Ejecución local
Abre `index.html` en un navegador. Para publicar, sube todo el contenido de esta carpeta a la raíz de la rama `main` de un repositorio público de GitHub.

## Publicación en GitHub Pages
1. Crea un repositorio público llamado `muebleria` (o usa el nombre que te haya indicado tu docente).
2. Sube `index.html`, `README.md` y las carpetas `css/`, `imagenes/` y `recursos/` a la raíz de la rama `main`.
3. En GitHub, abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**, rama `main` y carpeta `/ (root)`, y guarda.
5. Espera a que termine el despliegue y abre la URL que GitHub Pages muestre en esa pantalla.

URL del repositorio: `https://github.com/TU-USUARIO/muebleria`  
URL del sitio publicado: `https://TU-USUARIO.github.io/muebleria/`

**Importante:** reemplaza `TU-USUARIO` por tu nombre de usuario real de GitHub y coloca las URLs definitivas después de publicar el sitio. Las URLs anteriores son plantillas, no enlaces publicados verificados.
