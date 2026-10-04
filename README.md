Sayo Distribuciones: rediseño de página web

Taller práctico: Rediseñando una página web. Página institucional de Sayo Distribuciones, empresa dedicada a la distribución de productos de alta calidad en Río de Oro (Cesar) y Ocaña (Norte de Santander).

Autor: Andrea del Pilar Ruedas Rodríguez Curso: Desarrollo web  Fecha de entrega:30/09/2026

Framework elegido: Opción B, Bootstrap 5.3
Por qué elegí Bootstrap
Rapidez para un taller de 45 minutos. Bootstrap ya trae resueltos los componentes que pide el taller: barra de navegación con menú para celular (navbar), tarjetas (card), formularios (form-control) y botones. Eso me permitió dedicar el tiempo al diseño y al contenido, y no a construir cada pieza desde cero.
Cuadrícula responsiva integrada. El sistema de 12 columnas (row, col-md-6, col-lg-4) hace que las tres tarjetas de productos pasen de tres columnas en escritorio, a dos en tableta y a una en celular, sin escribir media queries para el diseño base.
Accesibilidad de serie. Los componentes de Bootstrap incluyen atributos aria-*, estados de foco y validación de formularios con mensajes de error. Los completé con etiquetas semánticas (header, nav, main, section, footer).
Personalización con CSS propio. Bootstrap da la estructura y el archivo Estilos.css define la identidad de la marca (azul, rojo, blanco y negro) mediante variables CSS. Para cambiar un color basta con editar una línea.
Documentación y soporte. Es un framework muy documentado y estable, lo que facilita mantener el sitio.
Por qué no Tailwind (Opción A)

Tailwind ofrece más control visual, pero obliga a escribir muchas clases utilitarias en cada elemento y, para un uso profesional, requiere un proceso de compilación. Para una página institucional pequeña y con poco tiempo, Bootstrap resulta más directo y deja el HTML más legible.

Requisitos del taller y cómo se cumplieron
Requisito	Dónde está	Cómo se resolvió
1. Header: logo y navegación principal	<header>	Navbar fija con el logo (sayo_img/logo_sayo.jpeg), cinco enlaces y botón de WhatsApp. En celular se convierte en menú desplegable.
2. Hero: título, subtítulo y botón CTA	#inicio	Título "Sayo Distribuciones", texto de presentación y los botones "Ver productos" y "Contáctanos".
3. Grid de cards: 3 tarjetas responsivas	#productos	Tres card en una cuadrícula de Bootstrap: 3 columnas en escritorio, 2 en tableta y 1 en celular.
4. Formulario: campos estilizados	#contacto	Nombre, correo, teléfono y mensaje con validación visual y mensajes de error. Al enviar abre WhatsApp con el mensaje armado.
5. Footer: enlaces y créditos	<footer>	Enlaces internos, datos de contacto, derechos reservados y créditos de diseño.
Estructura de archivos
Taller_rediseño_web/
├── index.html          Página principal
├── Estilos.css         Estilos propios (marca y componentes)
├── sayo_img/
│   └── logo_sayo.jpeg  Logo de la empresa
├── capturas/
│   ├── desktop.png     Captura en escritorio
│   └── mobile.png      Captura en celular
└── README.md           Este documento
Cómo ejecutarlo
Descarga o clona la carpeta.
Abre index.html en el navegador (doble clic). No requiere instalación.
Se necesita conexión a internet para cargar Bootstrap, los iconos y la fuente Manrope desde CDN.
Capturas de pantalla

Escritorio

Mostrar imagen

Celular

Mostrar imagen

Tecnologías
HTML5 semántico
CSS3 con variables personalizadas
Bootstrap 5.3.3 y Bootstrap Icons 1.11.3
Tipografía Manrope (Google Fonts)
JavaScript básico para el formulario y el año del pie de página
Créditos

Diseñado y desarrollado: Andrea del Pilar Ruedas Rodríguez - Sayo Distribuciones