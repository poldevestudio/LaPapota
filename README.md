# La Papota · Burger House & Papas Rústicas 🍔🍟

Sitio web oficial, catálogo interactivo y motor de pedidos de alta conversión desarrollado para **La Papota**, hamburguesería de Del Viso, Provincia de Buenos Aires.

---

## 📍 Datos Oficiales del Comercio (Ficha de Google Maps)
- **Nombre:** La Papota
- **Dirección Oficial:** Av. Constitución 371, Del Viso, Provincia de Buenos Aires (B1620).
- **Ficha Google Maps:** [La Papota en Google Maps](https://maps.app.goo.gl/3WmCiwgQY2oZThhP9)
- **Calificación en Google:** **4.3 ★**
- **Coordenadas GPS:** `-34.4106134, -58.7728164`
- **Plus Code:** `H6QG+QV Del Viso, Provincia de Buenos Aires`
- **Teléfono & WhatsApp Oficial:** `011 6415-8057` (`+54 9 11 6415-8057` / `5491164158057`)
- **Instagram Oficial:** [@papota_oficial](https://www.instagram.com/papota_oficial/)
- **Horarios:** Todos los días de 11:00 a 00:00 hs (Mediodía y Noche de corrido).

---

## 🛠️ Mejoras y Refactor Senior Aplicados

1. **Integración de Ficha Google Maps & Mapa con Pin Rojo:**
   - Mapa embebido interactivo centrado en `Av. Constitución 371` con el **marcador de pin rojo** activo y popup del local.
   - Botón directo de acción: *"CÓMO LLEGAR CON GOOGLE MAPS"* que abre la navegación GPS en celulares.
   - Badge de reputación: `⭐ 4.3 en Google Maps` integrado en el Hero y en la sección de ubicación.

2. **Mobile-First & Conversión (Estándares Poldev Estudio):**
   - **Botón Flotante Permanente de WhatsApp:** Con pulso luminoso animado y derivación directa al WhatsApp verificado (`+54 9 11 6415-8057`).
   - **Click-to-Chat segmentado por producto:** En cada tarjeta del menú (La Clásica, Doble Tentación, Papas de la Casa), el botón de pedido abre WhatsApp con el ítem precargado.
   - **Header sticky:** Navegación fluida y botón de pedido siempre visible en móviles.

3. **SEO Local & Rich Snippets:**
   - Metadatos Open Graph completos para generar tarjeta con foto al compartir por WhatsApp.
   - Datos estructurados Schema.org (`FastFoodRestaurant`) con coordenadas geográficas, teléfono, enlace a Google Maps, dirección en Del Viso y horarios.

---

## 📂 Arquitectura y Propuestas para el Cliente (Poldev Estudio)

Este proyecto está concebido bajo una **estrategia de dos propuestas escalables** para presentar a los dueños de La Papota:

### 1️⃣ Propuesta Básica — Landing de Presencia Local & Conversión Directa (`index.html`)
- **Objetivo:** Dar una imagen profesional, consolidar la identidad visual (mascota HD, fotos reales del local) y maximizar visitas presenciales y consultas rápidas.
- **Características:**
  - Ficha oficial de Google Maps con calificación real `4.3 ★`, horarios y botón GPS *"Cómo llegar"*.
  - Botón flotante permanente de WhatsApp y llamadas a la acción directas.
  - Sección de Menú con llamado directo a la carta.
  - Zero costo de mantenimiento ni servidores complejos.

### 2️⃣ Propuesta Pro — Menú Digital Interactivo & Motor de Pedidos Autónomo (`menu.html`)
- **Objetivo:** Agilizar las ventas en horas pico permitiendo que el cliente arme su propio pedido sin demorar al personal de mostrador.
- **Características:**
  - **Filtros por categoría:** Todo el menú, Hamburguesas, Papas rústicas, Lomitos & Milas, Super panchos, Bebidas.
  - **Carrito reactivo en tiempo real:** Selector de cantidades `[+]` / `[-]`, subtotales y total dinámico con persistencia local (`localStorage`).
  - **Modal de Checkout completo:**
    - Modalidad de entrega: *Envío a Domicilio (con campo de dirección)* o *Retiro en el Local (Take Away)*.
    - Opciones de pago: *Efectivo (con campo para indicar con cuánto abona y calcular vuelto)*, *Transferencia Bancaria*, o *Mercado Pago*.
    - Campo de aclaraciones/notas para la cocina (ej: "sin cebolla", "con aderezo aparte").
  - **Generador de Comanda a WhatsApp:** Formatea automáticamente un ticket estructurado y prolijo que se envía al WhatsApp oficial del local (`+54 9 11 6415-8057`) en 1 solo clic.
  - **100% Serverless & Cero Costo Fijo:** No requiere hosting con base de datos, no sufre caídas de servidor y se adapta perfectamente al celular o computadora que el comercio ya usa en la caja.

---

## 📂 Archivos del Proyecto
- `index.html`: Landing institucional / comercial de alta conversión (Propuesta 1).
- `menu.html`: Menú digital interactivo con carrito y generador de comanda a WhatsApp (Propuesta 2).
- `papa_logo.png`: Isotipo oficial de la mascota remasterizado en HD (1024x1024) con fondo transparente.
- `local_papota.jpg`: Fotografía real de la fachada y patio iluminado del local en Del Viso.
- `README.md`: Documentación técnica y comercial de la maqueta.

---
Desarrollado y optimizado por **Poldev Estudio** · Presencia Digital & Sitios Web de Alta Conversión.
