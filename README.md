# Alex González — sitio de marca personal

Sitio de una página para el perfil profesional de Alex González.
HTML y CSS en un solo archivo, sin compilación. Las animaciones corren con
GSAP y ScrollTrigger desde CDN.

## Contenido

- `index.html` — sitio completo (estructura, estilos y animaciones).
- `alex-gonzalez.webp` — retrato, 1080×1350, recortado a 4:5.

## Estructura de la página

1. **Portada** — nombre compuesto animado letra por letra y retrato enmarcado.
2. **Perfil** — trayectoria en prosa y contadores.
3. **Especialidades** — seis tarjetas en desplazamiento horizontal con anclaje.
4. **Trayectoria** — etapas profesionales y formación.
5. **Contacto** — enlace directo a LinkedIn.

## Detalles técnicos

- Nombre revelado letra por letra, agrupado por palabra para que nunca se corte.
- Secciones alternadas en contraste y palabras que se encienden al pasar.
- Desplazamiento horizontal anclado para las especialidades.
- Respeta `prefers-reduced-motion`: sin animaciones cuando el sistema lo pide.
- Tipografías: Satoshi y General Sans.
- Paleta: grafito `#131210`, cobre `#b0603a`, hueso `#f6f3ed`.

## Publicación

Sitio estático: cualquier servidor que entregue archivos lo publica sin
configuración adicional. La raíz del repositorio es la raíz del sitio.
