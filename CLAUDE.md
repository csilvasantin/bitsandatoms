# Proyecto 28 — Bits & Atoms

> Plataforma educativa de IA + IoT con interfaz web moderna.

## Contexto
Bits & Atoms es una plataforma web moderna para educación en IA e IoT. Proporciona una experiencia visual pulida con diseño dark-mode, tipografía variable (Inter + Space Grotesk), y paleta de colores moderno (púrpura, cian, rojo).

## Arquitectura
- **index.html**: aplicación web única con HTML + CSS incrustado + JavaScript vanilla
- Diseño responsive: navegación fija con scroll effects, hero section, contenido modular
- **Estilos**: CSS variables para tema, reset de estilos, efecto noise overlay, scrollbar personalizado
- **Fuentes**: Inter (body), Space Grotesk (headers) vía Google Fonts
- **Colores**:
  - Fondo: #060810
  - Acentos: #6c63ff (púrpura), #00d4aa (cian), #ff6b6b (rojo)
  - Texto: #e8eaf0, muted: #6b7280

## Componentes Visuales
- Navegación con logo y links (sticky, blur en scroll)
- CTA button con hover effect
- Hamburger menu (responsive)
- Noise overlay (SVG fractal turbulence)
- Smooth scroll behavior

## Notas para IAs
- Archivo único, fácil de desplegar sin build system
- Responsive design desde mobile (375px) a desktop (1280px+)
- Transiciones smooth (cubic-bezier) para UX fluida
- Color scheme coherente; respectar variables CSS al expandir
- Próximos pasos: componentes interactivos, animaciones scroll, integración de contenido, formularios
- Considerar accesibilidad: contrast ratios, ARIA labels si se expande
