# ChroniCaree - Landing Page

## Descripción del Proyecto

ChroniCaree es una plataforma digital innovadora que transforma el cuidado de enfermedades crónicas desde casa. Nuestra solución SaaS está diseñada específicamente para instituciones de salud que buscan optimizar el manejo de pacientes crónicos, democratizando el autocuidado y acercando a pacientes y equipos médicos herramientas digitales para un seguimiento proactivo, simple y centrado en la persona.

### Características principales:
- **Para Hospitales**: Sistema integral de gestión con panel centralizado y métricas en tiempo real
- **Monitoreo Continuo**: Seguimiento de síntomas, signos vitales y adherencia al tratamiento
- **Alertas Inteligentes**: Notificaciones automáticas para detectar patrones de riesgo
- **Analítica Clínica**: Reportes avanzados y predicciones basadas en IA
- **Seguridad Garantizada**: Cumplimiento HIPAA y protección de datos médicos
- **Gestión Móvil**: Acceso completo desde dispositivos móviles

## Paleta de Colores

- **Primary Color**: #26B5A6 - Color principal de la marca (botones, acentos, iconos)
- **Dark Blue**: #1A2A33 - Color secundario para textos y fondos oscuros
- **White**: #FFFFFF - Color base para fondos y textos en elementos oscuros
- **Accent Red**: #E63946 - Color de alerta para elementos críticos
- **Light Gray**: #F8F9FA - Color de fondo suave para secciones
- **Text Gray**: #6C757D - Color para textos secundarios y descripciones

## Tecnologías Utilizadas

- **HTML5** - Estructura semántica y accesible
- **CSS3** - Estilos avanzados con Flexbox, Grid y animaciones
- **JavaScript** (Vanilla) - Interactividad y animaciones dinámicas
- **Google Fonts** (Poppins) - Tipografía profesional y legible
- **Font Awesome** - Iconografía médica y de interfaz
- **Intersection Observer API** - Animaciones de entrada suaves
- **CSS Grid & Flexbox** - Layout responsivo y moderno

## Estructura del Proyecto

```
Landing-Page/
├── index.html                      # Página principal
├── README.md                       # Documentación del proyecto
└── src/
    ├── assets/
    │   └── img/                    # Imágenes del equipo y logos
    │       ├── log chroniCare.png  # Logo principal
    │       ├── AndreowSantiago.jpg # CEO & Fundador
    │       ├── Carlos Lopez.png    # CTO & Co-fundador
    │       ├── Schneider Delgado.png # Chief Medical Officer
    │       ├── SebastianMartin.jpeg # Chief Product Officer
    │       └── AlejandroBarturen.jpg # Chief Operations Officer
    ├── js/
    │   └── script.js               # JavaScript principal con animaciones
    └── styles/
        └── styles.css              # Estilos CSS con sistema de design
```

## Características Técnicas

### Animaciones y Efectos Visuales
- **Animaciones de entrada**: Intersection Observer para activar animaciones al hacer scroll
- **Hover effects avanzados**: Transformaciones 3D y efectos de profundidad
- **Parallax suave**: Efectos de movimiento sutil en elementos clave
- **Ripple effects**: Efectos de ondas en interacciones
- **Gradientes dinámicos**: Fondos con degradados y patrones

### Responsividad
- **Mobile First**: Diseño optimizado para dispositivos móviles
- **Breakpoints**: Tablet (768px+), Desktop (1024px+), Large Desktop (1200px+)
- **Grid Adaptativo**: Layouts que se ajustan según el tamaño de pantalla
- **Imágenes Responsivas**: Optimización automática de imágenes

### Accesibilidad
- **WCAG 2.1**: Cumplimiento con estándares de accesibilidad
- **Navegación por teclado**: Soporte completo para navegación sin mouse
- **Lectores de pantalla**: Semántica optimizada para asistentes
- **Reduced Motion**: Respeto por preferencias de movimiento reducido

### Performance
- **Lazy Loading**: Carga diferida de imágenes
- **CSS Optimizado**: Animaciones con GPU acceleration
- **Código Minificado**: Optimización para tiempos de carga rápidos
- **PWA Ready**: Preparado para funcionar como aplicación web progresiva

## Secciones de la Landing Page

### 1. **Header & Navigation**
- Logo responsivo
- Menú de navegación con smooth scroll
- Hamburger menu para móviles

### 2. **Hero Section**
- Título principal con gradiente animado
- Llamadas a la acción prominentes
- Fondo con patrones sutiles

### 3. **About Us**
- Cards visuales para Misión, Visión y Valores
- Estadísticas animadas con contadores
- Iconografía médica profesional

### 4. **Team Section**
- Perfiles del equipo directivo
- Fotos profesionales con efectos hover
- Información de roles y experiencia

### 5. **Services Section**
- Servicios para hospitales
- Sistema de membresías
- Cards destacadas con animaciones

### 6. **Testimonials**
- Testimonios de usuarios reales
- Cards con efectos de entrada
- Diseño enfocado en credibilidad

### 7. **Contact Section**
- Formulario de contacto funcional
- Información de contacto
- Integración con redes sociales

### 8. **Footer**
- Enlaces organizados por secciones
- Información legal
- Branding consistente

## Instalación y Uso

### Requisitos Previos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Servidor web local (opcional para desarrollo)

### Instalación Local
1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/chronicaree-landing.git
   ```

2. Navega al directorio del proyecto:
   ```bash
   cd chronicaree-landing
   ```

3. Abre `index.html` en tu navegador o usa un servidor local:
   ```bash
   # Con Python 3
   python -m http.server 8000
   
   # Con Node.js (si tienes http-server instalado)
   npx http-server
   ```

4. Visita `http://localhost:8000` en tu navegador

### Deployment
- **GitHub Pages**: Configuración automática desde el repositorio
- **Netlify**: Drag & drop de la carpeta del proyecto
- **Vercel**: Conexión directa con el repositorio Git

## Customización

### Colores
Modifica las variables CSS en `src/styles/styles.css`:
```css
:root {
    --primary-color: #26B5A6;
    --dark-blue: #1A2A33;
    --white: #FFFFFF;
    --accent-red: #E63946;
    --light-gray: #F8F9FA;
    --text-gray: #6C757D;
}
```

### Tipografía
Cambia la fuente principal en las variables CSS:
```css
:root {
    --font-primary: 'Poppins', sans-serif;
    --font-size-display: 48px;
    --font-size-h1: 36px;
    /* ... más tamaños */
}
```

### Animaciones
Ajusta las animaciones en `src/js/script.js`:
```javascript
// Configurar velocidad de animaciones
const observerOptions = {
    threshold: 0.1,
    rootMargin: '0px 0px -50px 0px'
};
```

## Contribución

1. **Fork** el proyecto
2. Crea una **rama** para tu feature (`git checkout -b feature/AmazingFeature`)
3. **Commit** tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. **Push** a la rama (`git push origin feature/AmazingFeature`)
5. Abre un **Pull Request**

## Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## Contacto

**ChroniCaree by Chronisys**
- Website: [www.chronicaree.com](https://www.chronicaree.com)
- Email: info@chronicaree.com
- LinkedIn: [@chronicaree](https://linkedin.com/company/chronicaree)

## Equipo de Desarrollo

- **Andreow Jomark Santiago Peña** - CEO & Fundador
- **Carlos Alberto Lopez Goitia** - CTO & Co-fundador  
- **Schneider Carlos Delgado Carrasco** - Chief Medical Officer
- **Sebastian Martin Beingolea Montalvo** - Chief Product Officer
- **Alejandro Nicolas Barturen Guzman** - Chief Operations Officer

---

*Transformando el cuidado de enfermedades crónicas desde casa* 🏥💚