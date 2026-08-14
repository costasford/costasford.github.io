# 💼 Interactive Business Card Portfolio

**A sophisticated digital business card inspired by Paul Allen's iconic design**

[![Live Site](https://img.shields.io/badge/Live%20Site-costasford.github.io-blue?style=for-the-badge)](https://costasford.github.io)
[![GitHub Pages](https://img.shields.io/github/deployments/costasford/costasford.github.io/github-pages?label=deployment&style=for-the-badge)](https://github.com/costasford/costasford.github.io/deployments)

---

## ✨ **Experience**

Visit **[costasford.github.io](https://costasford.github.io)** to experience an interactive portfolio that transforms the classic business card into a modern, elegant web experience.

### 🎯 **Key Features**

- **🌙 Dark/Light Theme Toggle** - Elegant animated switcher with system preference detection
- **🎴 3D Business Card** - Click to flip and explore projects with smooth CSS transforms  
- **🏷️ Interactive Filtering** - Click technology tags to filter projects dynamically
- **📱 Mobile Optimized** - Responsive design that feels native on all devices
- **♿ Accessibility First** - Full keyboard navigation, ARIA labels, and reduced motion support
- **⚡ Performance Focused** - Optimized loading, smooth animations, and efficient rendering

---

## 🏗️ **Architecture**

### **Single-File Mastery**
This portfolio demonstrates advanced frontend techniques in a clean, maintainable single-file architecture:

```
index.html (~1,100 lines)
├── 📱 Responsive HTML5 structure
├── 🎨 CSS custom properties for theming
├── ⚡ Vanilla JavaScript for interactions  
└── 🔧 Performance optimizations
```

### **Technical Highlights**

**🎨 CSS Excellence:**
- **CSS Custom Properties System** - a full token set for perfect theming
- **Advanced Animations** - Hardware-accelerated 3D transforms
- **Responsive Design** - Mobile-first with thoughtful breakpoints
- **Dark/Light Themes** - Seamless theme switching with persistence

**⚡ JavaScript Mastery:**
- **Event-Driven Architecture** - Clean, maintainable interactions
- **Performance Optimized** - Passive listeners and efficient DOM manipulation  
- **Accessibility Focused** - Comprehensive keyboard and screen reader support
- **Progressive Enhancement** - Graceful degradation for all users

---

## 🚀 **Quick Start**

### **View Live**
Simply visit **[costasford.github.io](https://costasford.github.io)** - no setup required!

### **Local Development**
```bash
# Clone the repository
git clone https://github.com/costasford/costasford.github.io.git
cd costasford.github.io

# Serve locally (choose your preferred method)
python -m http.server 8000        # Python
npx serve .                       # Node.js
php -S localhost:8000             # PHP

# Visit http://localhost:8000
```

---

## 🎨 **Design Philosophy**

### **Paul Allen Business Card Inspiration**
This portfolio transforms the iconic sophisticated business card aesthetic into an interactive digital experience:

- **Luxury Materials** → Subtle textures, embossed borders, and gradients
- **Premium Typography** → Fraunces serif + JetBrains Mono pairing
- **Elegant Layouts** → Perfect spacing and visual hierarchy  
- **Tactile Feel** → Interactive hover states and micro-animations

### **Modern Web Standards**
- **Progressive Enhancement** - Works everywhere, enhanced where supported
- **Accessibility First** - WCAG 2.1 AA compliant with keyboard navigation
- **Performance Budget** - Optimized for fast loading and smooth interactions
- **Mobile-First** - Touch-friendly design that scales beautifully

---

## 🛠️ **Technical Specifications**

### **Browser Support**
- ✅ Chrome 90+
- ✅ Firefox 88+  
- ✅ Safari 14+
- ✅ Edge 90+

### **Features Matrix**

| Feature | Desktop | Mobile | Accessibility |
|---------|---------|--------|---------------|
| 🌙 Theme Toggle | ✅ | ✅ | ✅ Keyboard + ARIA |
| 🎴 Card Flip | ✅ | ✅ | ✅ Focus Management |
| 🏷️ Tag Filtering | ✅ | ✅ | ✅ Screen Reader |
| 📊 Project Details | ✅ | ✅ | ✅ Keyboard Nav |
| ⚡ Animations | ✅ | ✅ | ✅ Reduced Motion |

### **Performance Metrics**
- **First Contentful Paint**: < 1.0s
- **Largest Contentful Paint**: < 1.5s  
- **Cumulative Layout Shift**: < 0.1
- **First Input Delay**: < 100ms
- **Bundle Size**: Single HTML file (~40KB)

---

## 💡 **Customization**

### **Theme Variables**
The entire color scheme is controlled through CSS custom properties:

```css
:root {
  /* Light Theme - warm cardstock */
  --bg-primary: #eee8db;
  --bg-secondary: #fbf8f1;
  --text-primary: #1c1917;
  --accent: #8a6a2f;
  /* ...plus shadows, borders, and transitions */
}

[data-theme="dark"] {
  /* Dark Theme - ink on slate */
  --bg-primary: #111110;
  --bg-secondary: #1b1a17;
  --text-primary: #ece7db;
  --accent: #c9a24b;
  /* ...perfectly balanced dark variants */
}
```

### **Project Data**
Projects are defined with structured data attributes:

```html
<li class="project-item" data-tech="React,TypeScript,Node.js" data-status="Live">
  <!-- Project content -->
</li>
```

---

## 🏆 **Recognition**

This portfolio represents:
- **Masterclass Frontend Development** - Advanced CSS and JavaScript techniques
- **Accessibility Champion** - Full WCAG compliance with keyboard navigation
- **Performance Excellence** - Optimized for speed and smooth interactions  
- **Design Innovation** - Creative transformation of classic business card concept

---

## 📄 **License**

MIT License - Feel free to use this design as inspiration for your own portfolio!

---

## 📬 **Contact**

**Costas Ford** - Problem Solver & Developer

- 📧 **Email**: [costasford@proton.me](mailto:costasford@proton.me)
- 💼 **LinkedIn**: [costasford](https://www.linkedin.com/in/costasford)
- 🐙 **GitHub**: [costasford](https://github.com/costasford)
- 📍 **Location**: San Francisco, CA

---

> *"Your personal site is your digital business card — make it unforgettable."*

**Built with ❤️ and vanilla web technologies** | **[View Live Site →](https://costasford.github.io)**