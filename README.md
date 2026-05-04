# Wonder Flowers 🇪🇸🌹

[![Live Demo index.html](https://img.shields.io/badge/Live%20Demo-index.html-brightgold?style=for-the-badge&logo=html5)](index.html)

## ✨ Sobre el Proyecto

**Wonder Flowers** es una experiencia de **ecommerce floral de lujo** inspirada en la estética **Floral Noir**. Un sitio web elegante con scroll suave, animaciones fluidas y diseño premium para una boutique floral high-end.

**Características principales**:
- 🎨 **Diseño Noir Premium**: Paleta oscura con acentos dorados (TailwindCSS customizado)
- 🌀 **Scroll Suave & Elegante**: `scroll-behavior: cubic-bezier(0.4, 0, 0.2, 1)` + snap sections + offsets perfectos
- 📱 **Responsive**: Optimizado mobile-first (Tailwind + custom breakpoints)
- ✨ **Animaciones**: Intersection Observer para fade-in suave + hover effects
- 🎯 **Navegación Fluida**: Anchor links precisos, back-to-top, scroll progress bar
- 🔤 **Tipografía Premium**: Noto Serif (headings) + Manrope (body)
- 📷 **Imágenes Editoriales**: High-end photography con AIDA CDN

## 🚀 Demo Files

| Archivo | Descripción | 
|---------|-------------|
| `index.html` | **Demo Principal** - Scroll suave, animaciones, todas las features |\n| `TODO.md` | Plan de desarrollo completado |\n| `README.md` | Documentación del proyecto |

**Ver Demo**: Abrir `index.html` en browser (Live Server recomendado)

## 🎨 Diseño & Features Técnicas

```
✨ Smooth Scroll Config:
  html { scroll-behavior: smooth }
  body { 
    scroll-behavior: cubic-bezier(0.4, 0, 0.2, 1);
    scroll-padding-top: 88px;  // Fixed header offset
    scroll-snap-type: y proximity;
  }
  sections { scroll-margin-top: 88px; scroll-snap-align: start }
```

- **Header Fijo**: 88px con progress bar dorada
- **Nav Anclas**: #hero, #gift-vault, #product-catalog, #wonder-experience, #concierge
- **Back-to-Top**: Auto-show + smooth scroll
- **Mobile Menu**: Hamburger con slide-in suave

## 📂 Estructura del Proyecto

```\nwonderFlowers.github.io/\n├── index.html       # ⭐ Demo principal (todas features)\n├── TODO.md          # Log de desarrollo\n└── README.md        # Este archivo\n```

## 🛠️ Tecnologías

```html
TailwindCSS 3.x (custom theme)
Google Fonts (Noto Serif + Manrope)
Material Symbols
AIDA CDN Images
Vanilla JS (IntersectionObserver + scroll events)
```

## 🎯 Secciones

1. **Hero** - Haute Botanique
2. **Gift Vault** - Colección Limitada 8 de Marzo
3. **Product Catalog** - Ramos, Cajas, Orquídeas
4. **Wonder Experience** - Packaging ritual
5. **Concierge** - Form + WhatsApp
6. **Footer** - Links minimalistas

## 🔮 Deployment Fácil

### GitHub Pages / Netlify
```
git init
git add .
git commit -m "Initial Wonder Flowers deploy"
git branch -M main
git remote add origin https://github.com/[TU-USUARIO]/wonderFlowers.github.io.git
git push -u origin main
```

**Live en 2 mins** 🚀

### VSCode Live Server\n```\nRight-click index.html → "Open with Live Server"\n```

## 📱 Responsive Breakpoints

| Tamaño | Clase Tailwind |
|--------|----------------|
| Mobile | `sm:` (640px+) |
| Tablet | `md:` (768px+) |
| Desktop | `lg:` (1024px+) |
| FullHD | `max-w-[1440px]` |

## 🎨 Customizaciones

### Colores (Material Design 3)
```css
primary: #f2ca50
primary-container: #d4af37
surface: #131313
on-surface: #e5e2e1
```

### Tipografía
```
Headlines: Noto Serif (Display)
Body: Manrope 400/500
Labels: Manrope Caps (tracking 0.15em)
```

## 🤝 Contribuir

1. Fork el repo
2. Crear feature branch (`git checkout -b feature/suave-scroll`)
3. Commit changes (`git commit -m 'Add smooth scroll'`)
4. Push (`git push origin feature/suave-scroll`)
5. Abrir Pull Request

## 📄 Licencia

**MIT License** - Úsalo libremente, solo menciona Wonder Flowers ✨

## 🙌 Agradecimientos

- **BLACKBOXAI**: Generación del scroll suave perfecto
- **TailwindCSS**: Framework brutal
- **Google Fonts**: Tipografía premium
- **AIDA CDN**: Imágenes editoriales AAA

---

**The Architecture of Bloom** 🌑🌹

*Preserving the ephemeral through precision and prestige.*

