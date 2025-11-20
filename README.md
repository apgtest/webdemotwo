
# 🌐 WebDemoTwo - Proyecto Web Demostrativo

![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Estado](https://img.shields.io/badge/Estado-Activo-brightgreen)
![Versión](https://img.shields.io/badge/Versión-2.0-blue)

## 📖 Sobre el Proyecto

**WebDemoTwo** Proyecto web demostrativo, donde aplico conceptos avanzados de desarrollo frontend y mejores prácticas de programación. Este proyecto  implementa diseños más complejos y funcionalidades interactivas.

### 🎯 Objetivo del Proyecto

Demostrar habilidades en desarrollo web frontend mediante la creación de un sitio moderno, responsive y funcional que sirva como portafolio de capacidades técnicas.

## ✨ Características Destacadas

- 🎨 **Diseño Moderno y Atractivo** - Interfaz visualmente impactante
- 📱 **100% Responsive** - Adaptable a todos los dispositivos
- ⚡ **Rendimiento Optimizado** - Carga rápida y eficiente
- 🎭 **Animaciones Fluidas** - Transiciones y efectos CSS3
- 🧩 **Componentes Modulares** - Código organizado y reutilizable
- 🌙 **Diseño Profesional** - Layout moderno y funcional
- ♿ **Accesible** - Siguiendo estándares de accesibilidad web
- 🔧 **Código Limpio** - Buenas prácticas y comentarios

## 🚀 Demo en Vivo

### 🌐 **[Ver Proyecto en Vivo](https://apgtest.github.io/webdemotwo/)**

> ¡Visita el sitio para ver todas las funcionalidades en acción!



## 🛠️ Stack Tecnológico

```
Frontend
├── HTML5        → Estructura semántica y moderna
├── CSS3         → Estilos avanzados, Grid, Flexbox
└── JavaScript   → Interactividad y lógica del cliente

Herramientas
├── Git          → Control de versiones
├── GitHub Pages → Hosting y deployment
└── VS Code      → Entorno de desarrollo
```

## 📋 Prerrequisitos

Para ejecutar este proyecto localmente necesitas:

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Editor de código (recomendado: VS Code)
- Git instalado en tu sistema
- Conocimientos básicos de HTML, CSS y JavaScript

## ⚙️ Instalación y Configuración

### 1️⃣ Clonar el Repositorio

```bash
git clone https://github.com/apgtest/webdemotwo.git
```

### 2️⃣ Navegar al Directorio

```bash
cd webdemotwo
```

### 3️⃣ Abrir en el Navegador

**Opción A: Directa**
- Simplemente abre `index.html` en tu navegador

**Opción B: Live Server (Recomendado)**
- Si usas VS Code, instala la extensión "Live Server"
- Click derecho en `index.html` → "Open with Live Server"

**Opción C: Servidor Local**

```bash
# Con Python 3
python -m http.server 8000

# Con Node.js (npx)
npx http-server

# Luego visita: http://localhost:8000
```

## 📁 Estructura del Proyecto

```
webdemotwo/
│
├── index.html              # Página principal
├── about.html              # Página sobre nosotros (opcional)
├── contact.html            # Página de contacto (opcional)
│
├── css/
│   ├── styles.css          # Estilos principales
│   ├── responsive.css      # Media queries y responsive
│   ├── animations.css      # Animaciones y transiciones
│   └── variables.css       # Variables CSS (colores, fuentes)
│
├── js/
│   ├── main.js             # JavaScript principal
│   ├── animations.js       # Lógica de animaciones
│   └── utils.js            # Funciones auxiliares
│
│ ├── images/             # Imágenes del proyecto
│   │   ├── hero/           # Imágenes hero/banner
│   │   └── icons/          # Íconos
│                
│

│
├── README.md               # Este archivo
└── LICENSE                 # Licencia del proyecto
```


## 💻 Fragmentos de Código Destacados

### Estructura HTML Semántica

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="WebDemoTwo - Proyecto web demostrativo">
    <title>WebDemoTwo | Desarrollo Web Moderno</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <nav class="navbar">
            <!-- Navegación -->
        </nav>
    </header>
    
    <main>
        <section class="hero">
            <!-- Contenido hero -->
        </section>
        
        <section class="features">
            <!-- Características -->
        </section>
    </main>
    
    <footer>
        <!-- Footer -->
    </footer>
    
    <script src="js/main.js"></script>
</body>
</html>
```

### CSS Grid Layout

```css
/* Layout moderno con CSS Grid */
.container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    padding: 2rem;
}

/* Animación suave */
.card {
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card:hover {
    transform: translateY(-10px);
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
}
```

### JavaScript Interactivo

```javascript
// Navegación suave
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function(e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        target.scrollIntoView({
            behavior: 'smooth',
            block: 'start'
        });
    });
});

// Menú móvil responsive
const menuToggle = document.querySelector('.menu-toggle');
const navMenu = document.querySelector('.nav-menu');

menuToggle.addEventListener('click', () => {
    navMenu.classList.toggle('active');
});
```

## 🎓 Conceptos Aplicados

Durante el desarrollo de este proyecto, implementé:

### HTML5
- ✅ Estructura semántica (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`)
- ✅ Meta tags para SEO y redes sociales
- ✅ Atributos ARIA para accesibilidad

### CSS3
- ✅ Flexbox y CSS Grid para layouts
- ✅ Variables CSS (custom properties)
- ✅ Media queries para responsive design
- ✅ Animaciones y transiciones suaves
- ✅ Pseudo-elementos y pseudo-clases

### JavaScript
- ✅ Manipulación del DOM
- ✅ Event listeners y handlers
- ✅ Funciones modernas (arrow functions, destructuring)
- ✅ Validación de formularios
- ✅ Smooth scroll

### Buenas Prácticas
- ✅ Código modular y organizado
- ✅ Comentarios descriptivos
- ✅ Nomenclatura consistente (BEM methodology)
- ✅ Optimización de recursos
- ✅ Versionamiento con Git

## 📱 Compatibilidad

Este proyecto es compatible con:

- ✅ **Chrome** (Última versión)
- ✅ **Firefox** (Última versión)
- ✅ **Safari** (Última versión)
- ✅ **Edge** (Última versión)
- ✅ **Opera** (Última versión)

### Responsive Breakpoints

```css
/* Mobile First Approach */
/* Mobile: < 768px (por defecto) */
/* Tablet: 768px - 1024px */
@media (min-width: 768px) { ... }

/* Desktop: > 1024px */
@media (min-width: 1024px) { ... }

/* Large Desktop: > 1440px */
@media (min-width: 1440px) { ... }
```

## 🔮 Roadmap / Mejoras Futuras

Funcionalidades planeadas para próximas versiones:

- [ ] Implementar modo oscuro/claro con toggle
- [ ] Agregar formulario de contacto funcional con validación
- [ ] Integrar animaciones más avanzadas (AOS, GSAP)
- [ ] Mejorar rendimiento con lazy loading de imágenes
- [ ] Implementar PWA (Progressive Web App)
- [ ] Agregar internacionalización (i18n) - Español/Inglés
- [ ] Tests automatizados (Jest)
- [ ] Optimización SEO avanzada

## 🐛 Problemas Conocidos

Actualmente no hay bugs reportados. Si encuentras alguno:

1. Abre un [Issue](https://github.com/apgtest/webdemotwo/issues)
2. Describe el problema detalladamente
3. Incluye screenshots si es posible
4. Menciona tu navegador y versión

## 🤝 Contribuciones

Las contribuciones son bienvenidas y apreciadas. Si deseas colaborar:

1. **Fork** el proyecto
2. Crea una **rama** para tu feature (`git checkout -b feature/MejoraNueva`)
3. **Commit** tus cambios (`git commit -m 'Add: nueva característica increíble'`)
4. **Push** a la rama (`git push origin feature/MejoraNueva`)
5. Abre un **Pull Request**

### Guía de Contribución

- Usa commits descriptivos
- Sigue la estructura de carpetas existente
- Comenta tu código cuando sea necesario
- Asegúrate de que el código sea responsive
- Prueba en diferentes navegadores

## 📚 Recursos de Aprendizaje

Si quieres aprender las tecnologías usadas en este proyecto:

- [MDN Web Docs](https://developer.mozilla.org/) - Documentación web
- [CSS Tricks](https://css-tricks.com/) - Tutoriales CSS avanzados
- [JavaScript.info](https://javascript.info/) - Guía completa de JS
- [Can I Use](https://caniuse.com/) - Compatibilidad de navegadores
- [W3C Validator](https://validator.w3.org/) - Validar HTML


## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

### ¿Qué significa esto?

Puedes:
- ✅ Usar comercialmente
- ✅ Modificar
- ✅ Distribuir
- ✅ Uso privado

Condiciones:
- 📝 Incluir la licencia MIT


## 📈 Estado del Proyecto

```
⚡ En Desarrollo Activo
```

Este proyecto está siendo continuamente mejorado. Revisa las actualizaciones frecuentemente.

---

<div align="center">

### ⭐ Si este proyecto te fue útil, considera darle una estrella ⭐



</div>

---


*Última actualización: Noviembre 2025*
