# 🍳 Landing Page Recetario

Una landing page moderna y hermosa para compartir tus recetas favoritas. Construida con **Astro** para máximo rendimiento y experiencia de usuario.

## 📋 Descripción

Landing Page Recetario es un proyecto web diseñado para presentar recetas de manera atractiva e interactiva. Perfecta para food bloggers, chefs amateurs o cualquiera que quiera compartir sus mejores creaciones culinarias.

### Características

- ✨ Diseño moderno y responsivo
- ⚡ Rendimiento ultrarrápido con Astro
- 🎨 Componentes reutilizables
- 📱 Optimizado para móvil y desktop
- 🚀 Listo para producción

## 🚀 Inicio Rápido

### Requisitos

- **Node.js** 18+ o superior
- **pnpm** (gestor de paquetes recomendado)

### Instalación

```bash
# Instalar dependencias
pnpm install

# Iniciar servidor de desarrollo
pnpm dev
```

El sitio estará disponible en `http://localhost:4321\`

## 📦 Comandos Disponibles

| Comando | Descripción |
|---------|-------------|
| `pnpm install` | Instala todas las dependencias del proyecto |
| `pnpm dev` | Inicia el servidor de desarrollo en \`localhost:4321\` |
| `pnpm build` | Construye el sitio para producción en \`./dist/\` |
| `pnpm preview` | Previsualiza el build de producción localmente |
| `pnpm astro ...` | Ejecuta comandos CLI de Astro |

## 📁 Estructura del Proyecto

```
├── public/              # Archivos estáticos públicos
├── src/
│   ├── assets/         # Imágenes, fuentes y otros recursos
│   ├── components/     # Componentes Astro reutilizables
│   ├── layouts/        # Plantillas de página
│   │   └── Layout.astro
│   ├── pages/          # Rutas y páginas del sitio
│   │   └── index.astro
│   └── styles/         # Estilos CSS globales
│       └── global.css
├── astro.config.mjs    # Configuración de Astro
├── tsconfig.json       # Configuración de TypeScript
└── package.json        # Dependencias y scripts
```

## 🛠️ Desarrollo

### Agregar nuevas recetas

1. Crea nuevos componentes en `src/components/`
2. Modifica las páginas en `src/pages/`
3. Los cambios se reflejan automáticamente en el servidor de desarrollo

### Personalización

- **Estilos**: Edita `src/styles/global.css`
- **Layout**: Modifica `src/layouts/Layout.astro`
- **Contenido**: Actualiza las páginas en `src/pages/`

## 📚 Recursos

- [Documentación oficial de Astro](https://docs.astro.build)
- [Guía de estructura de proyectos](https://docs.astro.build/en/basics/project-structure/)
- [Comunidad de Astro](https://astro.build/chat)

## 📝 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

---

## ¡Feliz cocina y a compartir tus mejores recetas! 👨‍🍳👩‍🍳