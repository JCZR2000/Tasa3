# 📊 Tasa3 - Calculadora de Cambio Material 3

**Tasa3** es una WebApp minimalista y ultra-rápida diseñada para realizar conversiones precisas entre Bolívares (VES) y las principales divisas del mercado venezolano (Dólar BCV, Euro BCV y USDT). 

Construida bajo los principios de **Material Design 3**, ofrece una experiencia de usuario limpia, adaptativa y visualmente atractiva.

![Versión](https://img.shields.io/badge/Version-3.0-blue?style=for-the-badge)
![Licencia](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

## ✨ Características Principales

* **⚡ Datos en Tiempo Real:** Consumo directo de API propia alojada en GitHub para asegurar tasas actualizadas.
* **🎨 Diseño Material You:** Interfaz elegante con bordes redondeados, tipografía clara y efectos de elevación.
* **🔄 Conversión Bidireccional:** Calcula de divisa a Bolívares y viceversa con un solo toque mediante el botón de intercambio.
* **🌓 Modo Oscuro Dinámico:** Soporte nativo para modo claro/oscuro que respeta las preferencias del sistema.
* **🌈 Personalización de Color:** Permite al usuario cambiar el color de acento de toda la aplicación.
* **📱 Totalmente Responsivo:** Experiencia optimizada para móviles y escritorio.

## 🛠️ Tecnologías Utilizadas

* **HTML5 / JavaScript (Vanilla):** Lógica pura para una carga instantánea.
* **Tailwind CSS:** Para un estilizado moderno y eficiente.
* **Material Design 3:** Guías de diseño para una estética de última generación.
* **GitHub Actions (Backend):** El JSON de tasas se actualiza automáticamente mediante un scraper externo.

## 🚀 Instalación y Uso

No requiere instalación. Al ser una Single Page Application (SPA), puedes ejecutarla de tres formas:

1.  **Directo:** Abre el archivo `index.html` en cualquier navegador moderno.
2.  **GitHub Pages:** Sube el código a un repositorio y activa "Pages" para tener tu propia URL pública.
3.  **Local Server:** Usa extensiones como *Live Server* en VS Code.

## 📁 Estructura del JSON de Datos

La aplicación consume los datos de la siguiente estructura:
```json
{
  "dolar": 00.00,
  "euro": 00.00,
  "usdt": 00.00
}
```

🤝 Créditos
Desarrollado por Juan / JCZR2000. Proyecto parte del ecosistema DigitalWorks.
