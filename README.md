# 🌸 BLOOM Experience - Landing Page

![BLOOM Logo](logo.png)

**El deseo empieza con una carta**

Landing page oficial de BLOOM Experience, un juego de cartas diseñado para parejas que desean reconectar a través del romance, las palabras y el deseo gradual.

---

## 📋 Descripción del Proyecto

BLOOM Experience es más que un juego de cartas; es una herramienta de reconexión emocional e íntima para parejas. Esta landing page presenta el producto con una estética elegante y sofisticada, utilizando tonos granate profundos, tipografía serif de lujo y un diseño responsive optimizado para conversión.

### ✨ Características Principales

- **Diseño Premium**: Paleta de colores en tonos granate, rose gold y dorados
- **Tipografía Elegante**: Playfair Display para títulos, Montserrat para cuerpo de texto
- **Efecto Seda de Lujo**: Fondo animado que simula pliegues de seda
- **Responsive Design**: Optimizado para dispositivos móviles, tablets y desktop
- **Alta Conversión**: Estructura de ventas con copywriting persuasivo
- **Animaciones Sutiles**: Efectos visuales que mejoran la experiencia sin distraer

---

## 🎨 Paleta de Colores

```css
--color-granate: #8b1a1e        /* Granate principal */
--color-granate-dark: #4a0a0d   /* Granate oscuro */
--color-rose-gold: #E8B4A3      /* Rosa dorado */
--color-coral: #F4A492           /* Coral */
--color-gold: #D4AF37            /* Dorado */
--color-cream: #FAF8F5           /* Crema */
```

---

## 🚀 Tecnologías Utilizadas

- **HTML5**: Estructura semántica y accesible
- **CSS3**: Estilos avanzados con animaciones y gradientes
- **JavaScript Vanilla**: Interactividad sin dependencias
- **Google Fonts**: Playfair Display, Montserrat, Cormorant Garamond
- **Responsive Design**: Mobile-first approach

---

## 📂 Estructura del Proyecto

```
bloom-landing/
│
├── bloom-landing.html    # Página principal
├── logo.png             # Logo de BLOOM (flor de loto)
├── README.md            # Este archivo
│
└── assets/              # Imágenes de las cartas (opcional)
    ├── Directa.png
    ├── Coqueteo.png
    ├── Exploracion.png
    ├── Retos.png
    ├── Potenciadores.png
    └── Ducha_Fria.png
```

---

## 🎯 Secciones de la Landing Page

1. **Hero Section**: Presentación con logo, título elegante y video de ventas
2. **¿Te suena familiar?**: 6 pain points que resuenan con el público objetivo
3. **Los Tres Niveles de BLOOM**: Explicación de las fases del juego
   - 🌅 Exploración (Dorado/Coral)
   - 💕 Coqueteo (Rosa Gold)
   - 🔥 Directa (Granate)
4. **Potenciadores**: Cartas especiales (Retos y Potenciadores)
5. **Seguridad y Consentimiento**: Carta "Ducha Fría"
6. **¿Para quién NO/SÍ es BLOOM?**: Segmentación de audiencia
7. **Testimonios**: Historias reales de reconexión
8. **Oferta Irresistible**: Pricing con stack de valor
9. **FAQ**: Preguntas frecuentes con acordeón

---

## 💻 Instalación y Uso

### Opción 1: Clonar el Repositorio

```bash
git clone https://github.com/tu-usuario/bloom-landing.git
cd bloom-landing
```

Abre `bloom-landing.html` en tu navegador favorito.

### Opción 2: GitHub Pages

1. Fork este repositorio
2. Ve a Settings → Pages
3. Selecciona la rama `main` como fuente
4. Tu landing estará disponible en: `https://tu-usuario.github.io/bloom-landing/`

### Opción 3: Despliegue en Netlify/Vercel

1. Conecta tu repositorio de GitHub
2. El despliegue será automático
3. Obtén tu URL personalizada

---

## ⚙️ Personalización

### Cambiar Colores

Edita las variables CSS en la sección `:root`:

```css
:root {
    --color-granate: #8b1a1e;
    --color-gold: #D4AF37;
    /* ... más variables */
}
```

### Modificar Textos

Todos los textos están en español y pueden editarse directamente en el HTML. Los elementos clave incluyen:

- Título principal: `<h2 class="bloom-title">`
- Slogan: `<p class="hero-slogan">`
- Precio: `<div class="precio">`

### Integrar Métodos de Pago

Añade tus enlaces de pago en los botones CTA:

```html
<a href="TU_ENLACE_DE_PAGO" class="btn btn-primary">
    Quiero Reconectar Ahora
</a>
```

### Conectar WhatsApp

Actualiza el botón flotante de WhatsApp:

```html
<a href="https://wa.me/593XXXXXXXXX" class="whatsapp-float">
```

---

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

---

## 🎨 Características de Diseño

### Animaciones

- **Fade In/Out**: Entrada suave de elementos
- **Float**: Logo flotante en sección de oferta
- **Breathe**: Efecto de respiración en fondos
- **Subtle Movement**: Movimiento sutil del gradiente de seda

### Interactividad

- **Carruseles**: Navegación de imágenes de cartas
- **Acordeón FAQ**: Preguntas expandibles
- **Hover Effects**: Efectos al pasar el mouse
- **Smooth Scroll**: Desplazamiento suave entre secciones

---

## 🔧 Mejoras Futuras

- [ ] Integración con pasarela de pagos (Stripe/PayPal)
- [ ] Sistema de cupones de descuento
- [ ] Chat en vivo para soporte
- [ ] A/B testing de variantes
- [ ] Analytics y tracking de conversiones
- [ ] Formulario de captura de emails
- [ ] Blog/contenido educativo sobre relaciones

---

## 📊 SEO y Performance

- Estructura HTML semántica
- Meta tags optimizados
- Imágenes con atributos alt
- Carga rápida (< 3 segundos)
- Mobile-friendly (Google Mobile-First)

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/NuevaCaracteristica`)
3. Commit tus cambios (`git commit -m 'Añadir nueva característica'`)
4. Push a la rama (`git push origin feature/NuevaCaracteristica`)
5. Abre un Pull Request

---

## 📄 Licencia

Este proyecto es propiedad de BLOOM Experience. Todos los derechos reservados.

---

## 📞 Contacto

- **tiktok**: @bloom-experiencie.com
- **Instagram**: @bloom-experiencie

---

## 🌟 Agradecimientos

Diseñado con 💜 para parejas que desean reconectar con su deseo y romance.

> "El deseo se cultiva, no aparece por arte de magia."

---

**BLOOM** - Creado por mujeres para mujeres que entienden que el cerebro es el órgano sexual más importante.

