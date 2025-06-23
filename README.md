# 🏥 Landing Page - Capacitación en Primeros Auxilios para Docentes

### Cruz Roja Argentina

Una landing page moderna y responsiva diseñada para promocionar cursos de primeros auxilios especializados para docentes de la Cruz Roja Argentina.

## 📋 Descripción del Proyecto

Esta landing page está diseñada para promocionar la capacitación en primeros auxilios específicamente adaptada para el entorno educativo. El sitio web presenta una solución integral para docentes que necesitan estar preparados ante emergencias médicas en el aula.

### 🎯 Objetivo Principal

Capacitar a docentes con técnicas de primeros auxilios adaptadas al entorno escolar, proporcionando herramientas para actuar correctamente ante emergencias médicas que puedan ocurrir durante el horario educativo.

## 🚀 Características Principales

### ✨ Funcionalidades

- **Diseño Responsive**: Compatible con dispositivos móviles, tablets y desktop
- **Navegación Suave**: Scroll suave entre secciones
- **Header Dinámico**: Cambia su apariencia al hacer scroll
- **Animaciones CSS**: Efectos visuales atractivos con fadeIn
- **Botón Flotante**: FAB (Floating Action Button) para volver al inicio
- **Menu Móvil**: Hamburger menu para dispositivos pequeños

### 📱 Secciones del Sitio

1. **Hero Section**: Presentación principal con estadísticas
2. **Problema**: Identificación de emergencias escolares comunes
3. **Solución**: Presentación del curso y sus beneficios
4. **Videos Demostrativos**: Videos de muestra de técnicas de primeros auxilios
5. **Testimonios**: Experiencias reales de docentes certificadas
6. **Precios**: Planes de capacitación disponibles
7. **CTA Final**: Llamada a la acción principal
8. **Footer**: Información de contacto y enlaces útiles

## 🎨 Paleta de Colores

### Colores Principales

| Color             | Hex       | Uso                                   | Preview                                                         |
| ----------------- | --------- | ------------------------------------- | --------------------------------------------------------------- |
| **Primary Red**   | `#d62d20` | Color principal de marca, botones CTA | ![#d62d20](https://via.placeholder.com/20/d62d20/000000?text=+) |
| **Secondary Red** | `#b91c1c` | Color secundario, hover states        | ![#b91c1c](https://via.placeholder.com/20/b91c1c/000000?text=+) |
| **Accent Blue**   | `#1e40af` | Acentos, iconos secundarios           | ![#1e40af](https://via.placeholder.com/20/1e40af/000000?text=+) |

### Colores Neutros

| Color           | Hex       | Uso                     | Preview                                                         |
| --------------- | --------- | ----------------------- | --------------------------------------------------------------- |
| **Light Gray**  | `#f8fafc` | Fondos de sección       | ![#f8fafc](https://via.placeholder.com/20/f8fafc/000000?text=+) |
| **Medium Gray** | `#64748b` | Texto secundario        | ![#64748b](https://via.placeholder.com/20/64748b/000000?text=+) |
| **Dark Gray**   | `#0f172a` | Texto principal, footer | ![#0f172a](https://via.placeholder.com/20/0f172a/000000?text=+) |

### Colores de Estado

| Color              | Hex       | Uso                        | Preview                                                         |
| ------------------ | --------- | -------------------------- | --------------------------------------------------------------- |
| **Success Green**  | `#059669` | Checkmarks, confirmaciones | ![#059669](https://via.placeholder.com/20/059669/000000?text=+) |
| **Warning Orange** | `#ea580c` | Alertas, advertencias      | ![#ea580c](https://via.placeholder.com/20/ea580c/000000?text=+) |

### Gradientes

```css
--gradient-primary: linear-gradient(135deg, #d62d20 0%, #b91c1c 100%);
--gradient-hero: linear-gradient(
  135deg,
  rgba(214, 45, 32, 0.95) 0%,
  rgba(185, 28, 28, 0.95) 100%
);
```

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica moderna
- **CSS3**: Estilos avanzados con variables CSS y Flexbox/Grid
- **JavaScript Vanilla**: Interactividad sin frameworks
- **Google Fonts**: Tipografía Inter
- **SVG**: Iconografía y patrones de fondo

## 📁 Estructura del Proyecto

```
Landing-CruzRoja/
├── assets/             # Recursos multimedia
│   ├── rcp.mp4        # Video demostración RCP (48MB)
│   ├── atragantamiento.mp4  # Video maniobra Heimlich (17MB)
│   └── explicacion.mp4      # Video motivacional (2.7MB)
├── index.html          # Archivo principal del sitio
└── README.md          # Documentación del proyecto
```

## 🎭 Componentes y Secciones Detalladas

### 🏠 Header / Navegación

- Logo de Cruz Roja Argentina
- Menú de navegación con enlaces ancla
- CTA button "Comenzar Ahora"
- Menú hamburger para móviles
- Efecto glassmorphism con backdrop-filter

### 🦸‍♀️ Hero Section

- Título impactante con llamada a la acción
- Descripción del valor propósito
- Dos botones CTA (primario y secundario)
- Estadísticas en grid (docentes certificados, satisfacción, etc.)
- Fondo con gradiente y patrón SVG

### ⚠️ Problem Section

- 6 tarjetas con problemas identificados:
  - Emergencias frecuentes
  - Tiempo crítico
  - Falta de preparación
  - Responsabilidad institucional
  - Confianza de padres
  - Desarrollo profesional

### 💡 Solution Section

- Layout de dos columnas (desktop)
- Lista de beneficios con checkmarks
- Preview del curso con módulos
- CTAs secundarios

### 🎥 Videos Section

- 3 videos demostrativos locales (formato 9:16 vertical):
  - **RCP (Reanimación Cardiopulmonar)**: Demostración de RCP en adulto mayor con paro cardíaco
  - **Maniobra de Heimlich**: Procedimiento para atragantamiento en adulto mayor
  - **¿Por qué inscribirse?**: Joven explicando los beneficios de capacitarse en el curso
- Videos locales almacenados en `/assets/`
- Thumbnails placeholder con gradientes de colores distintivos
- Modal responsive que se abre al hacer click en cualquier card
- Aspect ratio 9:16 optimizado para videos verticales
- Botón de play interactivo con hover effects
- Auto-reproducción al abrir modal
- Cierre con tecla ESC o click fuera del video
- Controles nativos del navegador
- Descripción detallada de cada procedimiento
- CTA integrada para ver el programa completo

### 💬 Testimonios

- 6 testimonios reales de docentes
- Cards con avatar, nombre, cargo y ubicación
- Experiencias específicas de uso en emergencias

### 💰 Pricing Section

- 3 planes de capacitación:
  - **Básico**: Gratuito
  - **Certificación Oficial**: $50,000 (destacado)
  - **Plan Institucional**: Consultar
- Card destacada con efecto "Más Popular"

### 📞 CTA Final

- Llamada a la acción principal
- Dos opciones: Curso gratis y llamada telefónica
- Fondo con gradiente principal

### 🦶 Footer

- 4 columnas de información
- Enlaces organizados por categorías
- Información de contacto
- Copyright y reconocimientos

## 📱 Responsive Design

### Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1199px
- **Desktop**: ≥ 1200px

### Adaptaciones Móviles

- Menú hamburger
- Grids adaptables
- Tipografía responsive con `clamp()`
- Spacing y padding optimizados
- CTAs de ancho completo en móvil

## ⚡ Performance y Optimización

### Técnicas Implementadas

- **CSS Variables**: Gestión eficiente de colores y valores
- **Lazy Loading**: Observador de intersección para animaciones
- **Smooth Scrolling**: Navegación fluida
- **Backdrop Filter**: Efectos modernos con buen rendimiento
- **Semantic HTML**: Mejor SEO y accesibilidad

### Animaciones

- `fadeInUp`: Entrada suave de elementos
- Hover effects en tarjetas y botones
- Transiciones suaves (0.3s ease)

## 🌐 SEO y Accesibilidad

### Meta Tags

- Viewport responsive
- Charset UTF-8
- Título descriptivo
- Lang="es" for Spanish content

### Accesibilidad

- Estructura semántica
- Contraste de colores adecuado
- Navegación por teclado
- Texto alternativo en elementos interactivos

## 📊 Métricas y KPIs

### Estadísticas Mostradas

- **5,000+** Docentes certificados
- **98%** Satisfacción
- **24/7** Acceso al curso
- **30 días** Garantía

## 🚀 Instalación y Uso

1. **Clonar o descargar** el proyecto
2. **Abrir** `index.html` en cualquier navegador moderno
3. **No requiere** servidor web (funciona con file://)
4. **Opcional**: Servir con un servidor local para mejor performance

```bash
# Con Python 3
python -m http.server 8000

# Con Node.js
npx serve .

# Con PHP
php -S localhost:8000
```

## 🔗 Enlaces Importantes

- **Plataforma de Capacitación**: [https://login-cruz-roja.vercel.app/](https://login-cruz-roja.vercel.app/)
- **Cruz Roja Argentina**: https://www.cruzroja.org.ar/
- **Email Capacitación**: capacitacion@cruzroja.org.ar
- **Teléfono**: (011) 1234-5678

## 👥 Target Audience

### Público Primario

- **Docentes de nivel inicial, primario y secundario**
- **Directivos educativos**
- **Personal escolar no docente**

### Características del Usuario

- Edad: 25-55 años
- Formación: Educativa/Pedagógica
- Motivación: Seguridad de estudiantes
- Necesidad: Capacitación profesional

## 🎨 Guía de Marca

### Tipografía

- **Primary**: Inter (Google Fonts)
- **Fallback**: -apple-system, BlinkMacSystemFont, sans-serif
- **Weights**: 400, 500, 600, 700, 800

### Iconografía

- Emojis para facilidad de implementación
- Cruz roja (✚) como símbolo de marca
- Checkmarks (✓) para beneficios

## 📈 Futuras Mejoras

### Funcionalidades Propuestas

- [ ] Formulario de registro funcional
- [ ] Integración con CRM
- [ ] Chat en vivo
- [ ] Testimonios en video
- [ ] Blog integrado
- [ ] Calculadora de ROI
- [ ] Comparador de planes

### Optimizaciones Técnicas

- [ ] Lazy loading de imágenes
- [ ] Service Worker para PWA
- [ ] Compresión de assets
- [ ] Analytics tracking
- [ ] A/B testing setup

## 🤝 Contribuciones

Para contribuir al proyecto:

1. Fork del repositorio
2. Crear branch feature (`git checkout -b feature/AmazingFeature`)
3. Commit cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push al branch (`git push origin feature/AmazingFeature`)
5. Abrir Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE.md](LICENSE.md) para detalles.

## 👨‍💻 Autor

Desarrollado para **Cruz Roja Argentina** - Capacitación Docente

---

### 🏥 ¿Listo para hacer tu aula más segura?

> _"La preparación de hoy es la diferencia del mañana. Cada docente capacitado es un héroe potencial en el aula."_

**[🚀 Comenzar Capacitación](https://login-cruz-roja.vercel.app/)**
