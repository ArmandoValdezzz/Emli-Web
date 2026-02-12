# ⚡ EMLI ABENSA  
## Ingeniería Eléctrica & Comercializadora

Sitio web corporativo de alto rendimiento desarrollado para **EMLI ABENSA**, diseñado para presentar servicios de **ingeniería eléctrica de potencia** y **suministro industrial especializado**, con una estética moderna e industrial.

---

## 🛠 Stack Tecnológico

| Tecnología | Descripción |
|------------|------------|
| **Framework** | Astro v4 — Generación de Sitio Estático (SSG) para máxima optimización de carga |
| **Estilos** | Tailwind CSS — Diseño responsive con utilidades personalizadas |
| **Lenguaje** | JavaScript / TypeScript |
| **Efectos Visuales** | Custom CSS Masks y Glassmorphism |

---

## 📂 Estructura del Proyecto

```bash
src/
│
├── components/        # Componentes modulares reutilizables
│   ├── Navbar.astro
│   ├── SeccionComercializadora.astro
│   ├── Contacto.astro
│   └── ...
│
├── layouts/           # Plantilla base HTML
│   ├── BaseLayout.astro
│   └── ...
│
├── pages/             # Rutas del sitio
│   ├── index.astro
│   ├── comercializadora.astro
│   └── ...
│
public/                # Assets estáticos
│   ├── logo-emli.svg
│   ├── iconos-servicios/
│   ├── fondos-industriales/
│   └── ...
```

---

## 🚀 Instalación y Desarrollo

### 1️⃣ Instalar dependencias

```bash
npm install
```

### 2️⃣ Iniciar servidor de desarrollo

```bash
npm run dev
```

El sitio estará disponible en:

```
http://localhost:4321
```

---

### 3️⃣ Compilar para producción

```bash
npm run build
```

Contiene el sitio optimizado listo para despliegue.

---

## 📝 Notas Técnicas

### 🔹 Efecto “Break the Box”

Se implementó posicionamiento `absolute` con `z-index` elevado para permitir que elementos visuales (como el logo “V” y transformadores) rompan la simetría del diseño, generando dinamismo visual.

---

### 🔹 Máscaras de Difuminado

Uso de:

```css
mask-image: radial-gradient(black, transparent);
```

Para fundir iconos y diagramas con el fondo corporativo azul `#1F4C95`.

---

### 🔹 Sombras Dinámicas (Ghost Divs)

Integración de elementos circulares con alto nivel de `blur` detrás de productos clave para generar profundidad visual sin afectar el rendimiento.

---

### 🔹 Responsive Design

Uso de breakpoints de Tailwind para:

- Ajustar visibilidad de elementos decorativos  
- Escalar imágenes correctamente  
- Optimizar experiencia en dispositivos móviles  

---

