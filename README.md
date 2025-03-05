# GDS Infraestructura - Documentación Técnica


## Descripción del Proyecto

Este proyecto consiste en la implementación del sitio web responsivo para GDS Infraestructura, una empresa peruana dedicada al diseño y elaboración de proyectos de ingeniería para edificaciones, con más de 10 años de experiencia en el sector.

## Enlace al Sitio

El sitio web se encuentra disponible en: [https://gds-infraestructura.com](https://gds-infraestructura.com)

## Retos Adicionales Implementados

### 1. Diseño Responsivo Completo
- Implementación de diseño adaptable para dispositivos móviles, tablets y escritorio utilizando Tailwind CSS
- Menú hamburguesa para dispositivos móviles
- Sistema de grid flexible para la organización de contenido en el footer

### 2. Efectos Visuales y de Interacción
- Transiciones suaves en elementos interactivos (hover)
- Efecto de escala en el botón flotante de WhatsApp
- Transparencias en la superposición de textos sobre imágenes

### 3. Integración de Mapas
- Incorporación de mapas de Google Maps para mostrar las dos ubicaciones de la empresa (Lima y Apurímac)
- Mapas responsivos que se adaptan al tamaño de pantalla

### 4. Botón Flotante de WhatsApp
- Implementación de un botón flotante de WhatsApp para contacto rápido
- Mensaje predefinido incluido en el enlace
- Efectos visuales al interactuar con el botón

### 5. Optimización de Imágenes
- Aplicación de técnicas de objeto-fit para optimizar la visualización de imágenes
- Control de tamaños de imagen para diferentes dispositivos

## Decisiones Técnicas Clave

### 1. Framework CSS: Tailwind
- Se optó por utilizar Tailwind CSS mediante CDN para un desarrollo rápido y eficiente
- Enfoque utility-first para la creación de componentes personalizados
- Uso de clases específicas para colores corporativos (#0D253F y #E67E22)

```html
<script src="https://cdn.tailwindcss.com"></script>
```

### 2. Estructuración del Código
- Organización semántica con etiquetas HTML5 (header, main, section, article, footer)
- Comentarios detallados para facilitar el mantenimiento futuro
- Agrupación lógica de componentes por secciones

### 3. Sistema de Navegación
- Menú adaptable a diferentes tamaños de pantalla
- Solución con checkbox oculto para el control del menú en dispositivos móviles
- Consistencia visual en los elementos de navegación

```html
<input type="checkbox" id="menu-toggle" class="hidden">
<label for="menu-toggle" class="text-white text-2xl cursor-pointer md:hidden">☰</label>
```

### 4. Paleta de Colores
- Uso consistente de la paleta corporativa:
  - Azul oscuro (#0D253F) como color principal
  - Naranja (#E67E22) como color de acento
  - Blanco para textos sobre fondos oscuros
- Implementación de efectos hover con variaciones de los colores base

### 5. Rendimiento y Accesibilidad
- Etiquetas alt descriptivas en todas las imágenes
- Atributos aria para mejorar la accesibilidad
- Carga diferida (lazy loading) en los mapas integrados

```html
<iframe class="w-full h-40 rounded-md" src="..." loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
```

### 6. Optimización para SEO
- Metadatos completos en el head
- Estructura jerárquica de encabezados
- URLs semánticas en los enlaces

## Estructura del Proyecto

```
/
├── index.html
├── compra.html
├── testimonio-bootstrap.html
├── img/
│   ├── logo-blanco.png
│   ├── tinkagds-scaled.jpg
│   ├── ic-cont-1.png
│   ├── ic-cont2.png
│   ├── dise2.png
│   ├── fondo-2.jpg
│   ├── tel1.png
│   ├── tel2.png
│   ├── tel3.png
│   └── ic-what.png
└── README.md
```

## Funcionalidades Implementadas

1. **Header con Navegación Responsiva**
   - Menú adaptable a diferentes dispositivos
   - Logo enlazado a la página principal

2. **Sección Hero**
   - Imagen a pantalla completa con texto superpuesto
   - Contenido centrado con fondo semi-transparente

3. **Tarjetas de Servicios**
   - Diseño con cambio de color al pasar el cursor
   - Iconos ilustrativos

4. **Sección "Sobre Nosotros"**
   - Presentación de la empresa con énfasis en su experiencia
   - Combinación de texto e imagen

5. **Footer Informativo**
   - Estructura en columnas para diferentes tipos de información
   - Integración de mapas para las ubicaciones
   - Enlaces de interés
   - Información de contacto

6. **Botón Flotante de WhatsApp**
   - Acceso rápido a contacto
   - Posición fija en la pantalla
   - Efectos visuales al interactuar

## Próximos Pasos y Mejoras

- Implementación de un formulario de contacto con validación
- Galería de proyectos completados
- Animaciones adicionales para mejorar la experiencia de usuario
- Optimización adicional para tiempos de carga

## Créditos

- Desarrollado por: PercyTech
- Cliente: GDS Infraestructura
- Año: 2025
