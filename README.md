# 🧮 Cálculo Simple — IVA 13% Reverse Calculator

> **[🌐 Live Demo](https://calculo-simple.vercel.app)**

A simple web tool to calculate the original price of a product before the 13% VAT (IVA) was applied.

---

## 🇺🇸 English

### About

**Cálculo Simple** is a lightweight web utility that solves a common everyday problem: given a final price that already includes Costa Rica's 13% VAT, what was the original price before tax?

Instead of doing the math manually, this tool gives you the answer instantly.

### 💡 How It Works

When a price has 13% VAT added, the formula to reverse it is:

```
Original Price = Final Price / 1.13
```

**Example:**
- Final price (with IVA): ₡11,300
- Original price (without IVA): ₡10,000

### ✨ Features

- ⚡ Instant calculation — no page reloads
- 📱 Fully responsive — works on mobile and desktop
- 🎨 Clean, minimal UI built with Tailwind CSS
- 🚀 Blazing fast — powered by Astro's static generation

### 🛠️ Tech Stack

| Technology | Description |
|---|---|
| [Astro](https://astro.build) | Static site framework |
| [Tailwind CSS v4](https://tailwindcss.com) | Utility-first styling |
| [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) | Calculation logic |
| [Vercel](https://vercel.com) | Deployment platform |

### 📁 Project Structure

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── assets/
│   │   └── astro.svg
│   ├── components/
│   │   └── Welcome.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

### ⚙️ Getting Started

**Prerequisites:** Node.js installed.

```bash
# 1. Clone the repository
git clone https://github.com/LUHECU/Calculo-Simple.git
cd Calculo-Simple

# 2. Install dependencies
npm install

# 3. Start the development server
npm run dev
```

The app will be available at `http://localhost:4321`.

### 🧞 Commands

| Command | Action |
|---|---|
| `npm install` | Install dependencies |
| `npm run dev` | Start local dev server at `localhost:4321` |
| `npm run build` | Build production site to `./dist/` |
| `npm run preview` | Preview production build locally |

### 📦 Deployment

This project is deployed on **[Vercel](https://vercel.com)**. Any push to `master` triggers an automatic deployment.

---

## 🇪🇸 Español

### Acerca del proyecto

**Cálculo Simple** es una herramienta web ligera que resuelve un problema cotidiano muy común: dado un precio final que ya incluye el IVA del 13% de Costa Rica, ¿cuál era el precio original antes del impuesto?

En lugar de hacer el cálculo manualmente, esta herramienta te da la respuesta de forma instantánea.

### 💡 ¿Cómo funciona?

Cuando a un precio se le ha sumado el 13% de IVA, la fórmula para revertirlo es:

```
Precio Original = Precio Final / 1.13
```

**Ejemplo:**
- Precio final (con IVA): ₡11.300
- Precio original (sin IVA): ₡10.000

### ✨ Funcionalidades

- ⚡ Cálculo instantáneo — sin recargas de página
- 📱 Totalmente responsivo — funciona en móvil y escritorio
- 🎨 UI limpia y minimalista con Tailwind CSS
- 🚀 Ultra rápido — impulsado por la generación estática de Astro

### 🛠️ Stack Tecnológico

| Tecnología | Descripción |
|---|---|
| [Astro](https://astro.build) | Framework de sitios estáticos |
| [Tailwind CSS v4](https://tailwindcss.com) | Estilos con clases utilitarias |
| [JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript) | Lógica del cálculo |
| [Vercel](https://vercel.com) | Plataforma de despliegue |

### 📁 Estructura del Proyecto

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── assets/
│   │   └── astro.svg
│   ├── components/
│   │   └── Welcome.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

### ⚙️ Primeros Pasos

**Requisitos previos:** Tener Node.js instalado.

```bash
# 1. Clonar el repositorio
git clone https://github.com/LUHECU/Calculo-Simple.git
cd Calculo-Simple

# 2. Instalar dependencias
npm install

# 3. Iniciar el servidor de desarrollo
npm run dev
```

La aplicación estará disponible en `http://localhost:4321`.

### 🧞 Comandos

| Comando | Acción |
|---|---|
| `npm install` | Instalar dependencias |
| `npm run dev` | Iniciar servidor local en `localhost:4321` |
| `npm run build` | Compilar el sitio para producción en `./dist/` |
| `npm run preview` | Previsualizar la build de producción localmente |

### 📦 Despliegue

Este proyecto está desplegado en **[Vercel](https://vercel.com)**. Cualquier push a `master` activa un despliegue automático.

---

<div align="center">
  <sub>Built with ❤️ by <a href="https://github.com/LUHECU">LUHECU</a></sub>
</div>
