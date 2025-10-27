# LGBT Libre

Sitio web institucional para LGBT Libre - Por una sociedad más justa e inclusiva.

## 🚀 Tecnologías

- HTML5
- Tailwind CSS v3.4
- PostCSS
- Autoprefixer

## 📋 Requisitos previos

- Node.js (versión 14 o superior)
- npm (incluido con Node.js)

## 🛠️ Instalación

1. **Clona el repositorio** (o descarga el proyecto):

```bash
git clone <url-del-repositorio>
cd lgbt-libre
```

2. **Instala las dependencias**:

```bash
npm install
```

## 🏃 Ejecución en desarrollo

Para iniciar el entorno de desarrollo con compilación automática de Tailwind CSS:

```bash
npm run dev
```

Este comando:
- Compila el archivo `src/styles.css` a `dist/styles.css`
- Observa cambios en tiempo real (modo watch)
- Recompila automáticamente cuando editas archivos HTML o CSS

## 🔨 Compilación para producción

Para compilar y minificar el CSS para producción:

```bash
npm run build-prod
```

O simplemente para compilar sin watch:

```bash
npm run build
```

## 📂 Estructura del proyecto

```
lgbt-libre/
├── dist/                  # CSS compilado (generado automáticamente)
│   └── styles.css
├── src/                   # Archivos fuente
│   └── styles.css        # Estilos de Tailwind + clases personalizadas
├── index.html            # Página principal
├── tailwind.config.js    # Configuración de Tailwind CSS
├── postcss.config.js     # Configuración de PostCSS
├── package.json          # Dependencias y scripts
└── README.md            # Este archivo
```

## 🎨 Personalización

### Colores

Los colores de marca están definidos en `tailwind.config.js`:

```javascript
colors: {
  brand: {
    50: '#fdf2f8',
    100: '#fce7f3',
    200: '#fbcfe8',
  }
}
```

### Clases personalizadas

Las clases CSS personalizadas están en `src/styles.css`:

- `.container-wide` - Contenedor ancho
- `.container-narrow` - Contenedor estrecho
- `.section` - Espaciado de secciones
- `.heading-hero` - Títulos principales
- `.heading-2` - Títulos de sección
- `.chip` - Etiquetas/badges
- `.card` - Tarjetas de contenido
- `.btn-*` - Botones (primary, accent, ghost)

## 🌐 Visualización

1. Asegúrate de que el servidor de desarrollo esté corriendo (`npm run dev`)
2. Abre `index.html` en tu navegador
3. Para desarrollo local, puedes usar una extensión como **Live Server** en VS Code

## 📝 Scripts disponibles

- `npm run dev` - Inicia el modo desarrollo con watch
- `npm run build` - Compila el CSS una vez
- `npm run build-prod` - Compila y minifica para producción

## 🌓 Modo oscuro

El sitio incluye soporte para modo oscuro mediante la clase `dark` en el elemento `<html>`. El switch de tema está implementado con JavaScript y guarda la preferencia en `localStorage`.

## 📱 Responsive Design

El sitio está completamente optimizado para:
- 📱 Móviles (< 640px)
- 📱 Tablets (640px - 1024px)
- 💻 Desktop (> 1024px)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo LICENSE para más detalles.

## 📧 Contacto

Desarrollado con ❤️ para LGBT Libre