# AIDataCore - Página Web Corporativa

Una página web moderna y profesional para AIDataCore, empresa especializada en servicios y consultoría de inteligencia artificial y ciencia de datos.

## 🚀 Características

- **Diseño Responsivo**: Optimizado para desktop, tablet y móvil
- **Animaciones Suaves**: Efectos visuales atractivos y profesionales
- **Navegación Intuitiva**: Menú de navegación suave con scroll automático
- **Formulario de Contacto**: Sistema de contacto con validación
- **SEO Optimizado**: Estructura HTML semántica
- **Velocidad Optimizada**: CSS y JavaScript optimizados para rendimiento

## 📁 Estructura de Archivos

```
/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # Funcionalidad JavaScript
├── .gitignore          # Archivos a ignorar en Git
└── README.md          # Documentación
```

## 🎨 Secciones Incluidas

### 1. **Header/Navegación**
- Logo y branding de AIDataCore
- Menú de navegación responsivo
- Efecto de scroll en el header

### 2. **Hero Section**
- Mensaje principal con el slogan de la empresa
- Botones de llamada a la acción
- Estadísticas de la empresa
- Fondo con patrón de red neural

### 3. **Servicios**
- 6 servicios principales:
  - Modelos de Lenguaje (LLM)
  - Análisis Predictivo
  - Ciencia de Datos
  - Automatización IA
  - Machine Learning
  - Arquitectura Cloud
- Cards interactivas con hover effects

### 4. **Sobre Nosotros**
- Descripción de la empresa
- Características principales
- Imagen representativa

### 5. **Contacto**
- Información de contacto
- Formulario funcional
- Notificaciones de éxito

### 6. **Footer**
- Enlaces adicionales
- Redes sociales
- Copyright

## 🛠️ Personalización

### Cambiar Colores
Los colores principales se pueden modificar en `styles.css`:

```css
/* Color principal azul oscuro */
#1e40af, #1d4ed8, #2a3d69

/* Color secundario amarillo */
#fbbf24, #f59e0b

/* Colores de texto */
#1e293b, #64748b, #475569
```

### Modificar Contenido
1. **Información de la empresa**: Editar en `index.html` las secciones correspondientes
2. **Servicios**: Modificar las cards en la sección `#servicios`
3. **Contacto**: Actualizar información en la sección `#contacto`

### Agregar Funcionalidad al Formulario
Para conectar el formulario a un servicio real, modificar en `script.js`:

```javascript
// Reemplazar la simulación con una llamada real a tu API
fetch('/api/contact', {
    method: 'POST',
    headers: {
        'Content-Type': 'application/json',
    },
    body: JSON.stringify(formObject)
})
```

## 📱 Responsive Design

La página está optimizada para:
- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px  
- **Mobile**: < 768px

## 🔧 Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: 
  - Flexbox y Grid
  - Animations y Transitions
  - Media Queries
  - Custom Properties
- **JavaScript ES6+**:
  - Intersection Observer API
  - Event Listeners
  - DOM Manipulation
- **Font Awesome**: Iconografía
- **Google Fonts**: Tipografía (Inter)

## 🚀 Cómo Usar

1. **Abrir directamente**: Simplemente abre `index.html` en tu navegador
2. **Servidor local**: Para mejor rendimiento, usa un servidor local:
   ```bash
   # Python
   python -m http.server 8000
   
   # Node.js
   npx serve .
   
   # VS Code Live Server
   Instala la extensión "Live Server" y haz clic derecho → "Open with Live Server"
   ```

## 🌐 Deployment con GitHub Pages

### Paso 1: Subir a GitHub

1. **Crear repositorio en GitHub:**
   ```bash
   # Inicializar Git en el proyecto
   git init
   
   # Agregar todos los archivos
   git add .
   
   # Hacer commit inicial
   git commit -m "🚀 Initial commit: AIDataCore website"
   
   # Conectar con repositorio remoto
   git remote add origin https://github.com/TU_USUARIO/aidatacore-website.git
   
   # Subir a GitHub
   git push -u origin main
   ```

2. **O usando GitHub Desktop:**
   - Abre GitHub Desktop
   - Arrastra la carpeta del proyecto
   - Haz commit y push

### Paso 2: Configurar GitHub Pages

1. **En tu repositorio de GitHub:**
   - Ve a **Settings** (Configuración)
   - Scroll down hasta **Pages**
   - En **Source**, selecciona **Deploy from a branch**
   - Selecciona **main** branch
   - Carpeta **/ (root)**
   - Click **Save**

2. **¡Listo!** Tu sitio estará disponible en:
   ```
   https://TU_USUARIO.github.io/aidatacore-website/
   ```

### Paso 3: Dominio Personalizado (Opcional)

Si tienes un dominio propio:

1. **Crear archivo CNAME:**
   ```bash
   echo "www.aidatacore.com" > CNAME
   git add CNAME
   git commit -m "Add custom domain"
   git push
   ```

2. **Configurar DNS:**
   - Agregar registro CNAME que apunte a `TU_USUARIO.github.io`

### Actualizaciones Futuras

Para actualizar el sitio:
```bash
# Hacer cambios en los archivos
git add .
git commit -m "✨ Update: descripción de cambios"
git push
```

GitHub Pages se actualizará automáticamente en 1-2 minutos.

## 📊 Performance

- **Carga rápida**: CSS y JS optimizados
- **Imágenes ligeras**: Uso de iconos SVG y Font Awesome
- **Animaciones suaves**: 60fps en dispositivos modernos
- **CDN Gratis**: GitHub Pages incluye CDN global

## 🔄 Actualizaciones Futuras

Posibles mejoras que se pueden implementar:

1. **Blog/Noticias**: Sección de artículos y casos de éxito
2. **Portfolio**: Galería de proyectos realizados
3. **Testimonios**: Opiniones de clientes
4. **Multi-idioma**: Soporte para inglés/español
5. **CMS Integration**: Conexión con sistemas de gestión de contenido
6. **Analytics**: Google Analytics o similar
7. **PWA**: Progressive Web App features

## 🆘 Soporte

Si necesitas ayuda para personalizar o implementar la página web:

1. Revisa la documentación en los comentarios del código
2. Las clases CSS están bien organizadas y comentadas
3. El JavaScript incluye explicaciones de cada función

## 🔗 Enlaces Útiles

- **GitHub Pages Docs**: https://docs.github.com/en/pages
- **Dominio Personalizado**: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
- **Font Awesome**: https://fontawesome.com/
- **Google Fonts**: https://fonts.google.com/

## 📄 Licencia

Este proyecto es de uso libre para AIDataCore y puede ser modificado según las necesidades de la empresa.

---

**Desarrollado con ❤️ para AIDataCore**  
*Convirtiendo desafíos en estrategias con inteligencia hecha a medida*

**🌐 Live Demo**: https://TU_USUARIO.github.io/aidatacore-website/ 