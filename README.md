# 🛍️ El Universo de las Compras — Tienda online (legado)

Tienda pública de un solo archivo (`index.html`): catálogo con búsqueda en
tiempo real, filtros por categoría, variantes de talla y color, carrito y
pedido directo por **WhatsApp**. Los datos se leen de **Firebase Firestore**
en vivo.

> **Estado:** legado. La versión activa es
> [`juanguzmanjim1210-stack/Eluniversodelascompras`](https://github.com/juanguzmanjim1210-stack/Eluniversodelascompras)
> (Next.js 16 + PostgreSQL), desplegada en
> <https://eluniversodelascompras-alpha.vercel.app>.

## ✨ Funciones

- 🔍 Búsqueda y filtrado de productos en tiempo real
- 🏷️ Categorías, variantes (talla / color / precio) y stock
- 🖼️ Galería de imágenes con lightbox
- 🛒 Carrito con badge y resumen
- 💬 Botón de WhatsApp con el mensaje ya rellenado
- 📱 Responsive (móvil, tablet, escritorio)
- ⚡ Sin build: Tailwind y Firebase por CDN

## 🚀 Uso

```bash
npx serve .
```

Producción: <https://eluniversodelascompras.vercel.app>

## 📁 Estructura

```
index.html   # página completa: markup + estilos + lógica Firestore
```

## 🛠️ Tecnologías

HTML5 · Tailwind CSS (CDN) · Firebase JS SDK 8 (CDN) · Font Awesome 6

## 📄 Licencia

MIT
