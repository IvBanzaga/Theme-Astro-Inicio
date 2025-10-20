
# 🚀 Plantilla Astro Minimal

Una plantilla base moderna para proyectos Astro con Tailwind CSS, lista para producción y personalización.

## ✨ Características principales

- ⚡ **Astro 5**: Framework web moderno y ultrarrápido
- 🎨 **Tailwind CSS 4**: Utilidades CSS listas para usar
- 📱 **Responsive**: Diseño adaptable a cualquier dispositivo
- ♿ **Accesible**: Mejores prácticas de accesibilidad
- 🛡️ **SEO Optimizado**: Meta tags y estructura semántica
- 🧩 **Componentes reutilizables**: Estructura clara y escalable

---

## 🛠️ Instalación rápida

Puedes crear un nuevo proyecto basado en esta plantilla con:

```sh
npm create astro@latest -- --template github:IvBanzaga/theme-astro
# o usando pnpm
yarn create astro --template IvBanzaga/theme-astro
# o clona el repositorio manualmente
git clone https://github.com/IvBanzaga/theme-astro.git
cd theme-astro
pnpm install
pnpm dev
```

---

## 📁 Estructura del proyecto

```text
/
├── public/           # Archivos estáticos (imágenes, fuentes, etc.)
├── src/
│   ├── assets/       # Recursos como imágenes o fuentes
│   ├── components/   # Componentes Astro y UI
│   ├── layout/       # Layouts reutilizables
│   ├── pages/        # Páginas del sitio (rutas)
│   └── styles/       # Hojas de estilo globales
├── package.json      # Dependencias y scripts
└── astro.config.mjs  # Configuración de Astro
```

---

## 🧑‍💻 Comandos útiles

Todos los comandos se ejecutan desde la raíz del proyecto:

| Comando              | Acción                                                        |
|----------------------|--------------------------------------------------------------|
| `pnpm install`       | Instala las dependencias                                      |
| `pnpm dev`           | Inicia el servidor de desarrollo en `localhost:4321`          |
| `pnpm build`         | Genera el sitio listo para producción en `./dist/`            |
| `pnpm preview`       | Previsualiza el sitio generado localmente                     |
| `pnpm astro ...`     | Ejecuta comandos CLI de Astro (`astro add`, `astro check`, etc)|

---

## 📚 Recursos y documentación

- [Documentación oficial de Astro](https://docs.astro.build)
- [Tailwind CSS](https://tailwindcss.com/docs/installation)
- [Discord de Astro](https://astro.build/chat)

---

¡Personaliza esta plantilla y crea tu web moderna en minutos!
