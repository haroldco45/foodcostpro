# 🍳 FoodCost Pro — Control Gastronómico
**Desarrollada por Vibras Positivas HM — Derechos de Autor Reservados**

## Descripción
Aplicación web progresiva (PWA) para el control de costos gastronómicos. Ideal para restaurantes, chefs, emprendedores de alimentos y cualquier negocio gastronómico.

## Funcionalidades

### 📈 Dashboard
- Resumen estadístico: total de recetas, ingredientes, food cost promedio y ganancia total
- Ranking de recetas por rentabilidad (mejor a peor FC)
- Alertas automáticas de recetas con food cost elevado

### 📋 Recetas
- Creación y edición de recetas con ingredientes vinculados
- Cálculo automático de costo por porción con conversión de unidades
- Ajuste de merma automático por ingrediente
- Food cost calculado en tiempo real
- Indicador visual (verde/amarillo/rojo) por receta

### 🥦 Ingredientes
- Base de datos de ingredientes con categorías
- Costo por unidad, unidad de medida y % de merma
- Proveedor asociado
- Buscador en tiempo real

### 🍽️ Menú / Carta
- Organización de platos por categoría
- Vinculación a recetas para costo automático
- Análisis de rentabilidad por plato

### 🧮 Calculadora
- **Calculadora de Food Cost**: ingresa costo + precio → obtiene FC%, ganancia y margen
- **Precio Sugerido**: ingresa costo + % objetivo → obtiene precio recomendado
- **Calculadora de Merma**: peso bruto, neto → % merma y costo real

### ⚙️ Configuración
- Nombre del negocio y moneda
- % Food Cost objetivo y alerta personalizables
- Exportar/Importar datos en JSON
- Instalación PWA

## Instalación como App

### Android (Chrome)
1. Abre en Chrome
2. Toca el banner de instalación O el menú (⋮) → "Agregar a pantalla de inicio"

### iOS (Safari)
1. Abre en Safari
2. Toca el ícono compartir 🔗
3. "Agregar a pantalla de inicio"

### Desktop (Chrome/Edge)
1. Ícono de instalación en la barra de direcciones
2. Click → "Instalar"

## Estructura de Archivos
```
foodcost-pwa/
├── index.html      ← App principal
├── manifest.json   ← Configuración PWA
├── sw.js           ← Service Worker (offline)
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── README.md
```

## Tecnologías
- HTML5 + CSS3 + JavaScript vanilla
- LocalStorage para persistencia de datos
- Service Worker para funcionamiento offline
- Web App Manifest para instalación nativa
- Google Fonts (Playfair Display + DM Sans)

## Deploy recomendado
- **Netlify**: arrastrar la carpeta → URL instantánea
- **GitHub Pages**: subir repositorio → activar Pages

---
*FoodCost Pro v1.0 — Vibras Positivas HM — Caucasia, Antioquia, Colombia*
