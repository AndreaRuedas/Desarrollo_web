Sayo Distribuciones – Rediseño de página web

Página corporativa para Sayo Distribuciones (Río de Oro, Cesar), con cobertura en Ocaña, Norte de Santander y alrededores.

Framework elegido: Opción A (Tailwind CSS)

Para este taller elegí Tailwind CSS por estas razones:

Diseño propio sin plantillas: Tailwind no trae componentes prediseñados, así que la página se ve única y acorde a la marca de Sayo, no como un sitio genérico.
Estilos directamente en el HTML: con clases utilitarias (bg-azul, rounded-2xl, p-8) se ajusta cada elemento sin saltar entre archivos ni inventar nombres de clases.
Responsive simple: los prefijos md: y lg: cambian el diseño según la pantalla. Las 3 tarjetas pasan de 1 columna (móvil) a 2 (tablet) y 3 (escritorio) con md:grid-cols-2 lg:grid-cols-3.
Colores de la marca en un solo lugar: azul, rojo y negro se definen una vez en la configuración de Tailwind y se reutilizan en toda la página.
Ligero: no hay JavaScript de framework; solo un pequeño script para abrir el menú en móvil.
Tailwind vs. Bootstrap: Bootstrap es más rápido con componentes listos, pero deja un aspecto más reconocible y genérico. Tailwind da más control visual.
Herramientas
HTML5 y CSS3 (archivos separados)
Tailwind CSS (por CDN)
Google Fonts (Bricolage Grotesque y Source Sans 3)
npm / live-server para la vista previa local
Identidad visual

Colores de la empresa: azul, rojo, blanco y negro, definidos como variables CSS