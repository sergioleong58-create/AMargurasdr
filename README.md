# AMargurasdr
Aquí tienes un texto largo, profesional y sumamente detallado diseñado para el archivo `README.md` del repositorio de la página web. Está estructurado siguiendo las mejores prácticas del desarrollo web moderno y enriquecido con toda la información técnica, de diseño y contextual deducida a partir del código fuente de tu `index.html`.

---

# Agrupación Musical Virgen de la Amargura - Sitio Web Oficial 🎺🥁

¡Bienvenido al repositorio del sitio web oficial de la **Agrupación Musical Virgen de la Amargura** de Santander (Cantabria)! Este proyecto comprende el desarrollo de una plataforma web estática, adaptativa (responsive) y de alto impacto visual, diseñada para difundir la historia, la música, el patrimonio y la agenda de la banda decana de Santander, una institución con más de 70 años de trayectoria ininterrumpida.

El sitio actúa como el portal de referencia tanto para los componentes de la agrupación como para hermandades, seguidores del mundo de la música procesional y entidades civiles interesadas en la contratación de la banda.

---

## 📌 Índice

1. [Descripción General](https://www.google.com/search?q=%23-descripci%C3%B3n-general)
2. [Características Principales de la Web](https://www.google.com/search?q=%23-caracter%C3%ADsticas-principales-de-la-web)
3. [Estructura del Sitio y Navegación](https://www.google.com/search?q=%23-estructura-del-sitio-y-navegaci%C3%B3n)
4. [Análisis de Diseño y Arquitectura de CSS](https://www.google.com/search?q=%23-an%C3%A1lisis-de-dise%C3%B1o-y-arquitectura-de-css)
* [Paleta de Colores (Variables CSS)](https://www.google.com/search?q=%23paleta-de-colores-variables-css)
* [Componentes Clave Analizados](https://www.google.com/search?q=%23componentes-clave-analizados)


5. [Estrategia de Diseño Adaptativo (Responsive)](https://www.google.com/search?q=%23-estrategia-de-dise%C3%B1o-adaptativo-responsive)
6. [Estructura de Archivos del Proyecto](https://www.google.com/search?q=%23-estructura-de-archivos-del-proyecto)
7. [Tecnologías Utilizadas](https://www.google.com/search?q=%23-tecnolog%C3%ADas-utilizadas)
8. [Despliegue y Mantenimiento](https://www.google.com/search?q=%23-despliegue-y-mantenimiento)
9. [Créditos e Institución](https://www.google.com/search?q=%23-cr%C3%A9ditos-e-instituci%C3%B3n)

---

## 📖 Descripción General

La página web ha sido concebida bajo un enfoque estético elegante e institucional, combinando la solemnidad propia de las marchas procesionales y la Semana Santa con patrones de diseño modernos basados en la experiencia de usuario (UX).

A través del archivo principal `index.html`, la web sirve como landing page unificada que centraliza las últimas novedades de la temporada (como la actuación confirmada en las Fiestas de la Virgen de la Cama en Escalante), introduce un manifiesto del vertiginoso crecimiento musical y humano que ha vivido la banda en los últimos dos años, y distribuye al usuario de forma intuitiva hacia el resto de las secciones específicas del sitio mediante un sistema híbrido de menú de navegación y un grid de tarjetas interactivas.

---

## ⚡ Características Principales de la Web

* **Navegación Fluida e Híbrida:** Cuenta con una barra de navegación fija superior (`navbar`) acompañada de un menú lateral desplegable (`sidebar`) gestionado mediante transiciones suaves de CSS, proporcionando accesibilidad en cualquier nivel de scroll.
* **Hero Section de Alto Impacto:** Un encabezado principal que utiliza una imagen de fondo representativa con un degradado oscuro superpuesto para optimizar la legibilidad. Incorpora el escudo de la agrupación (`escudo.png`) mediante filtros visuales avanzados y un efecto interactivo de micro-zoom al posicionar el cursor (`:hover`).
* **Grid de Navegación Visual (Main Grid):** En lugar de un menú de texto plano aburrido, la web implementa un mosaico modular de tarjetas interactivas que invitan al usuario a explorar las diferentes secciones mediante imágenes llamativas, badges informativos y sutiles animaciones dinámicas (como el desplazamiento horizontal de flechas indicadoras en el hover).
* **Sección de Noticias Dinámica integrada en Grid:** Maquetación moderna en formato de tarjeta principal apaisada con una subdivisión interna óptima (40% imagen / 60% contenido escrito), diseñada específicamente para resaltar comunicados importantes y agendas detalladas.
* **Optimización del Rendimiento:** Al ser un sitio web puramente estático (HTML5 y CSS3 nativo), la velocidad de carga es ultra-rápida, carece de dependencias de pesadas librerías de terceros o frameworks de JavaScript innecesarios, y minimiza las peticiones HTTP.

---

## 🗺️ Estructura del Sitio y Navegación

El ecosistema de la web se divide en varias páginas conectadas mediante enlaces absolutos y relativos presentes en el menú de navegación lateral:

1. **Inicio (`index.html`):** Portal de bienvenida, resumen institucional, últimas noticias y accesos rápidos.
2. **Historia:** Dividida minuciosamente en tres subsecciones de gran valor documental:
* *La Virgen* (`HISTORIA VIRGEN DE LA AMARGURA.html`)
* *La Banda* (`HISTORIA DE LA BANDA.html`): Información sobre los más de 70 años como banda decana.
* *San Miguel* (`HISTORIA A.M.C. SAN MIGUEL.html`): Contexto o vinculación histórica asociada.


3. **Música (`REPERTORIO.html`):** Catálogo de marchas clásicas, composiciones infantiles y piezas festivas/pasacalles.
4. **Componentes (`COMPONENTES.html`):** Espacio dedicado a homenajear y presentar a los músicos de la agrupación.
5. **Uniformidad (`UNIFORMIDAD.html`):** Explicación del patrimonio textil e histórico de su indumentaria, inspirada en la Infantería de Marina española con rigor militar.
6. **Actuaciones (`ACTUACIONES.html`):** Calendario oficial, histórico de estaciones de penitencia, procesiones y eventos civiles.
7. **Contacto (`CONTACTO.html`):** Formulario o vías directas para nuevas incorporaciones o contrataciones.
8. **Redes Sociales (`REDES.html`):** Enlaces consolidados a las comunidades virtuales de la banda.
9. **Vídeos de Marchas (`VIDEOTECA.html`):** Sección multimedia para revivir actuaciones y ensayos en alta definición.

---

## 🎨 Análisis de Diseño y Arquitectura de CSS

El diseño del sitio web está impulsado por una hoja de estilos interna incrustada en el `<head>`. Destaca por una meticulosa selección tipográfica (`Segoe UI`, limpia y legible) y el uso de variables nativas de CSS (`:root`) que garantizan la consistencia cromática.

### Paleta de Colores (Variables CSS)

```css
:root { 
    --granate: #800000;   /* Color institucional principal, transmite solemnidad y pasión */ 
    --dorado: #d4af37;    /* Color de realce y patrimonio, evoca la ornamentación sacra y el metal */ 
    --negro: #1a1a1a;     /* Fondos oscuros para footers y barras laterales, alto contraste */ 
    --crema: #fdfaf5;     /* Fondo general de la página, suaviza la lectura frente al blanco puro */ 
    --blanco: #ffffff;    /* Fondos de tarjetas y contenedores de texto limpios */ 
    --texto: #2c2c2c;     /* Color base para el cuerpo de texto, evita la fatiga visual */ 
}

```

### Componentes Clave Analizados

* **El Escudo del Hero (`.escudo-adaptado`):** En lugar de insertarse como una imagen plana, se posiciona de manera absoluta en el centro del Hero, sirviendo de trasfondo elegante a los textos principales. Cuenta con un filtro CSS avanzado (`filter: drop-shadow(...) brightness(...) contrast(...)`) que le dota de un resplandor dorado simulado sin requerir edición de imágenes previa.
* **Las Tarjetas del Grid (`.nav-card`):** Utilizan la propiedad `overflow: hidden` emparejada con un contenedor de imagen (`.card-img-wrap`). Al pasar el ratón por encima (`:hover`), la imagen interna escala un 10% (`transform: scale(1.1)`) mediante una transición de `0.6s ease`, logrando un efecto de zoom elegante sin desbordar los bordes redondeados de la tarjeta.
* **La Caja de Inspiración (`.inspiracion-box`):** Actúa como un elemento destacado con bordes dorados e iluminación interna (`box-shadow: inset ...`). Contiene el escudo principal con animaciones que rotan levemente la imagen (`rotate(2deg) scale(1.1)`) al interactuar con ella, reforzando la marca institucional.

---

## 📱 Estratega de Diseño Adaptativo (Responsive)

El sitio web está diseñado bajo el paradigma de *Responsive Web Design*, asegurando una visualización óptima desde pantallas de escritorio 4K hasta teléfonos móviles compactos.

* **Puntos de Ruptura (Media Queries):**
* `max-width: 992px / 900px` (Tablets y Laptops pequeñas): El grid principal (`.main-grid`) y la sección mixta pasan de estructuras multicolumna a distribuciones verticales de una sola columna. Las tarjetas de noticias se reorganizan eliminando la disposición horizontal para que la imagen se posicione sobre el texto. El padding de los contenedores disminuye para maximizar el espacio en pantalla.
* `max-width: 768px` (Tablets verticales): El escudo central del Hero se escala proporcionalmente (de `650px` a `340px` / `240px`) y sus títulos principales disminuyen de tamaño (`font-size`) para evitar desbordamientos horizontales.
* `max-width: 480px` (Smartphones modernos): La tipografía del logotipo de la barra de navegación se compacta, el espaciado entre letras (`letter-spacing`) disminuye y elementos de aviso global como el `.banner-fijo` inferior se vuelven estrechos adaptando la fuente a un tamaño legible pero discreto (`0.75rem`).



---

## 📂 Estructura de Archivos del Proyecto

Para que el proyecto funcione correctamente, la raíz del servidor web o del repositorio debe mantener una organización armónica de los ficheros enlazados en el código:

```text
├── index.html                           # Página principal del sitio web (Código analizado)
├── HISTORIA VIRGEN DE LA AMARGURA.html  # Página sobre la advocación/titular de la agrupación
├── HISTORIA DE LA BANDA.html            # Página de la trayectoria de la agrupación
├── HISTORIA A.M.C. SAN MIGUEL.html      # Página histórica de la banda o asociación vinculada
├── REPERTORIO.html                      # Catálogo musical de marchas y pasacalles
├── COMPONENTES.html                     # Listado o galería de los músicos actuales
├── UNIFORMIDAD.html                     # Detalles de la vestimenta militar (Infantería de Marina)
├── ACTUACIONES.html                     # Agenda y contratos de la agrupación
├── CONTACTO.html                        # Información de contacto y formularios
├── REDES.html                           # Enlaces directos a plataformas sociales
├── VIDEOTECA.html                       # Galería de clips de vídeo musicales
│
├── escuadrone.png                       # Icono de la web (Favicon) y logotipo decorativo
├── escalante.jpeg                       # Imagen miniatura de la noticia de Escalante
├── Gemini_Generated_Image_...png       # Fondo visual para la videoteca destacada
└── [Imágenes Adicionales de Soporte]
    ├── WhatsApp Image 2026-03-03...jpeg # Fondo del Hero principal y uniformidad
    ├── WhatsApp Image 2026-05-20...jpeg # Imágenes para el bloque de Música e Historia
    └── Ayuntanmiento.jpeg               # Imagen de los componentes en el Ayuntamiento

```

---

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Marcado semántico estructurado utilizando etiquetas modernas como `<nav>`, `<main>`, `<section>`, `<article>` y `<footer>` que favorecen el posicionamiento SEO y la accesibilidad.
* **CSS3 Nativo:** Estilos avanzados basados en Grid Layout, Flexbox para alineaciones internas de navegación, Variables de CSS para tematización centralizada, Filtros Gráficos y Media Queries para un diseño 100% responsivo.
* **Vanilla JavaScript (Recomendado para producción):** El HTML cuenta con los identificadores `menuBtn`, `sidebar` y `overlay`. Se sugiere incluir al final del `body` el siguiente fragmento de código para dinamizar el menú lateral sin recurrir a frameworks:

```javascript
document.getElementById('menuBtn').addEventListener('click', function() {
    document.getElementById('sidebar').classList.toggle('active');
    document.getElementById('overlay').classList.toggle('active');
});

document.getElementById('overlay').addEventListener('click', function() {
    document.getElementById('sidebar').classList.remove('active');
    document.getElementById('overlay').classList.remove('active');
});

```

---

## 🚀 Despliegue y Mantenimiento

Al tratarse de código puro de cliente, este sitio web puede ser alojado de manera gratuita y permanente en plataformas de hosting estático modernas como:

* **GitHub Pages:** Basta con subir los archivos a un repositorio público o privado y activar la opción de despliegue desde la rama `main`.
* **Vercel / Netlify:** Conexión directa al repositorio Git con builds inmediatas ante cada cambio realizado.

### Para realizar actualizaciones de contenido (Mantenimiento):

1. **Modificar Noticias:** Busque la sección `<section class="seccion-noticias">` en el archivo `index.html` para cambiar las fechas, títulos o textos del evento (ej. Actualizar la fecha posterior al evento de Escalante del 22 de Agosto).
2. **Modificar Rutas de Imágenes:** Asegúrese de que las fotografías de los ensayos o actuaciones que reemplace mantengan los nombres de archivo especificados en los estilos inline de las tarjetas (ej. `background-image: url('Ayuntanmiento.jpeg');`), o actualice la ruta correspondientemente en el código fuente.

---

## 👑 Créditos e Institución

Este sitio web es propiedad intelectual y cultural de la **Agrupación Musical Virgen de la Amargura de Santander**. Refleja el orgullo, el crecimiento vertiginoso en lo musical y humano experimentado en los últimos años y el compromiso inquebrantable de una de las agrupaciones insignias de la música cofrade de Cantabria.

*¡Sones de fe y tradición en el corazón de Santander!* 🕊️✨
