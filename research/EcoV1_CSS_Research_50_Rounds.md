# EcoV1 CSS Research — 50 rondas

Objetivo: mejorar la experiencia visual/móvil del EcoV1 Bot Economy Lab sin alterar lógica económica, balance ni comportamiento de bots.

Criterio: investigar primero, implementar después. Prioridad: claridad, sensación de juego, retención, velocidad de lectura, uso con una mano, accesibilidad, rendimiento móvil y mínima carga cognitiva.

## Rondas
01. Touch targets: objetivo mínimo práctico 44–48 px. DECISIÓN: botones principales >=48px en móvil.
02. Safe areas iPhone: respetar notch/Dynamic Island/home indicator. DECISIÓN: padding con env(safe-area-inset-*).
03. Full-bleed game UI: usar pantalla completa pero contenido dentro de márgenes seguros. DECISIÓN: fondo full-bleed, controles inset.
04. Dark UI contrast: subir contraste entre superficie, borde y texto. DECISIÓN: tres niveles de panel y texto secundario más legible.
05. Visual hierarchy: KPIs deben leerse en menos de un segundo. DECISIÓN: barra KPI compacta y sticky.
06. Dashboard cognition: mostrar lo accionable antes de exploración. DECISIÓN: Mercado, Producción y Contrato ganan prioridad visual.
07. Progressive disclosure: no todo debe gritar a la vez. DECISIÓN: tarjetas secundarias más calmadas.
08. Game feel: feedback instantáneo en botones. DECISIÓN: active scale/translate + transición corta.
09. Motion discipline: animar para comunicar, no decorar. DECISIÓN: animaciones pequeñas y funcionales.
10. Reduced motion: respetar prefers-reduced-motion. DECISIÓN: desactivar transiciones/animación cuando se solicite.
11. Mobile one-hand reach: acciones frecuentes deben ser grandes y cercanas. DECISIÓN: acciones de producción envuelven y ocupan ancho útil.
12. Mobile card density: demasiado contenido vertical mata ritmo. DECISIÓN: reducir paddings secundarios y compactar metadata.
13. Market scanning: precio debe dominar sobre nombre/metadata. DECISIÓN: precio grande + tendencia en cápsula.
14. Buy/sell distinction: color semántico consistente. DECISIÓN: comprar neutro/azul; vender verde; peligro rojo.
15. Urgency cues: caducidad debe destacar progresivamente. DECISIÓN: barra de perecederos con mayor contraste y estado danger.
16. Inventory readability: cada slot debe sentirse como objeto, no celda de admin. DECISIÓN: slots con relieve, icon-like spacing y estados claros.
17. Empty slots: deben ser visibles sin competir. DECISIÓN: vacío con menor contraste.
18. Rot state: debe generar rechazo inmediato. DECISIÓN: borde rojo, fondo tóxico y botón de limpieza bien definido.
19. Bot identity: personalidad persistente debe verse rápido. DECISIÓN: tarjetas de bot con encabezado fuerte y meter de rivalidad.
20. Rivalry legibility: rivalidad debe sentirse como sistema jugable. DECISIÓN: barra naranja/roja más visible.
21. Contract urgency: contrato es oportunidad, no texto. DECISIÓN: tarjeta premium con borde/acento dorado y CTA prominente.
22. Progress psychology: warehouse debe enseñar cercanía a recompensa. DECISIÓN: barra más gruesa, glow moderado, título claro.
23. Order book scanning: BID/ASK debe alinearse y diferenciarse. DECISIÓN: filas con columnas firmes y chips semánticos.
24. Activity feed noise: feed debe ser historia, no terminal. DECISIÓN: eventos separados en bloques suaves y timestamp discreto.
25. Sticky context: jugador no debe perder Oro/tiempo al hacer scroll. DECISIÓN: top/KPIs sticky en móvil y desktop.
26. Responsive breakpoints: no colapsar tarde. DECISIÓN: 900px como transición principal y ajustes extra bajo 560px.
27. Fluid typography: evitar saltos bruscos. DECISIÓN: clamp() en título/precios/KPI.
28. Component responsiveness: preparar cards para contenedores estrechos. DECISIÓN: minmax() y auto-fit donde sea seguro.
29. Mobile viewport: evitar dependencias frágiles de 100vh. DECISIÓN: usar min-height:100dvh.
30. Overscroll: evitar sensación de web genérica. DECISIÓN: overscroll-behavior-y:contain.
31. Touch behavior: eliminar highlight agresivo. DECISIÓN: -webkit-tap-highlight-color transparente con estados propios.
32. Focus visibility: no perder accesibilidad teclado. DECISIÓN: :focus-visible ring de alto contraste.
33. Native controls dark mode: select debe integrarse. DECISIÓN: color-scheme:dark.
34. Scrollbars: feed debe verse limpio sin esconder funcionalidad. DECISIÓN: scrollbar fino solo donde exista soporte.
35. Performance: evitar efectos caros repetidos. DECISIÓN: sombras moderadas; blur limitado; sin partículas ni filtros continuos.
36. CSS animation performance: priorizar transform/opacity. DECISIÓN: press/hover solo con transform/filter cortos.
37. Reflow control: tarjetas independientes. DECISIÓN: contain:paint donde no rompe layout.
38. Hover vs touch: hover no debe ser requisito. DECISIÓN: toda señal crítica existe también en estado estático/active.
39. Small screens 360px: botones no deben quedar microscópicos. DECISIÓN: producción 1 columna en ancho muy estrecho.
40. Landscape phone: aprovechar ancho. DECISIÓN: productos pueden mantenerse en 3 columnas cuando haya ancho real.
41. Header clarity: subtítulo actual es largo. DECISIÓN: CSS limita ancho y reduce presencia sin cambiar copy.
42. Information rhythm: alternar superficies evita bloque uniforme. DECISIÓN: card principal, card secundaria y panel interior diferenciados.
43. Premium affordance: oportunidad valiosa debe sentirse valiosa. DECISIÓN: contrato con tono oro, no verde genérico.
44. Danger semantics: reset no debe competir con acciones de juego. DECISIÓN: reset visualmente peligroso pero menos dominante que CTAs de progreso.
45. Pause state discoverability: botón pausa debe conservar tamaño constante. DECISIÓN: min-width táctil.
46. Visual status without icons dependency: cero assets nuevos para esta ronda. DECISIÓN: CSS puro, sin dependencia externa.
47. Browser compatibility: evitar features necesarias para funcionar. DECISIÓN: enhancement progresivo; grid/flex/clamp/env como base moderna.
48. Preserve experiment validity: no tocar lógica ni balances durante cambio visual. DECISIÓN: stylesheet separado y workflow inyecta CSS.
49. Reversibility: CSS V2 debe poder quitarse sin alterar V1. DECISIÓN: archivo ecov1-ui-v2.css independiente.
50. Testability: cada push debe refrescar Pages automáticamente. DECISIÓN: workflow copia CSS e inyecta link al preview publicado.

## Fuentes y comunidades revisadas
- Apple Human Interface Guidelines: Layout y Game Controls.
- W3C/WCAG: target size, focus-visible, prefers-reduced-motion.
- MDN: env(safe-area-*), clamp(), container/containment, overscroll, ARIA live regions, color-scheme.
- Android Accessibility: targets de 48dp.
- NN/g: dashboards y lectura a simple vista.
- GitHub: game-hud, browser-game/mobile responsive projects, vanilla HTML/CSS game interfaces.
- Reddit y foros de jugadores: quejas recurrentes sobre HUD saturado, botones pequeños, Auction House poco legible y exceso de pasos.

## Resultado de investigación antes de implementar
La V2 visual debe parecer un juego económico móvil, no un panel administrativo. El cambio se limitará a presentación: jerarquía, densidad, táctil, contraste, safe area, estados y feedback. La lógica económica queda intacta.
