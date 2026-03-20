# Overlap Guatemala — Sitio Web Oficial

Sitio web corporativo para **Overlap Guatemala**, empresa especializada en blindaje automotriz premium. Construido con Astro 5 y Tailwind CSS v4.

## Stack

- [Astro 5](https://astro.build) — framework estático con SSG
- [Tailwind CSS v4](https://tailwindcss.com) — utilidades CSS (vía plugin Vite)
- [astro-icon](https://www.astroicon.dev) + [Tabler Icons](https://tabler.io/icons) + [MDI](https://materialdesignicons.com) — iconografía
- Vanilla JS — interactividad (navbar, tabs de niveles, formulario)
- Google Fonts — Bebas Neue (display) + DM Sans (body)

## Estructura del proyecto

```
/
├── public/
│   └── assets/          # Logo, imágenes de vehículos, íconos
├── src/
│   ├── components/
│   │   ├── Navbar.astro
│   │   ├── Hero.astro
│   │   ├── NivelesBlindaje.astro
│   │   ├── PorQueOverlap.astro
│   │   ├── Materiales.astro
│   │   ├── Compatibilidad.astro
│   │   ├── Testimonios.astro
│   │   ├── Cotizar.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css   # Variables CSS, fuentes, utilidades globales
├── astro.config.mjs
└── package.json
```

## Secciones

| Sección | Descripción |
|---|---|
| Hero | Pantalla completa con headline, CTA y vehículo blindado |
| Niveles de Blindaje | Selector interactivo Nivel II / III / IV / V con imágenes |
| Por qué Overlap | Propuesta de valor, stats y certificaciones |
| Materiales | Vidrios, acero balístico y suspensión reforzada |
| Compatibilidad | Marquee animado con marcas de vehículos |
| Testimonios | 3 testimonios de clientes con indicadores de confianza |
| Cotizar | Formulario de cotización compacto + datos de contacto |
| Footer | Navegación, contacto, redes sociales |

## Identidad de marca

| Token | Valor |
|---|---|
| Negro | `#0A0A0A` |
| Blanco | `#FFFFFF` |
| Amarillo | `#F5C800` |
| Fuente display | Bebas Neue |
| Fuente body | DM Sans |

## Comandos

```bash
# Instalar dependencias
npm install

# Servidor de desarrollo
npm run dev

# Build de producción
npm run build

# Preview del build
npm run preview
```

## Contacto

- **Teléfono / WhatsApp:** +502 4245 3899
- **Email:** info@overlapgt.com
- **Web:** overlapgt.com
