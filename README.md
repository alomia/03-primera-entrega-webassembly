# 📘 Primera Entrega – WebAssembly

Proyecto desarrollado para la asignatura **Fundamentos Web**.
Primera entrega académica enfocada en la construcción de un sitio web multipágina utilizando tecnologías modernas del ecosistema frontend.

---

## 📌 Descripción del Proyecto

Este proyecto consiste en la creación de un sitio web informativo sobre **WebAssembly**, cumpliendo con los requisitos establecidos por el docente:

* ✅ 1 página principal (Historia del tema)
* ✅ 1 página sobre los desarrolladores
* ✅ 1 página con alternativas al tema principal
* ✅ Uso de imágenes y videos
* ✅ Aplicación de estilos, colores y etiquetas correctamente estructuradas
* ✅ Múltiples páginas enlazadas correctamente

El objetivo no es únicamente cumplir con HTML y CSS básicos, sino aplicar los fundamentos aprendidos utilizando herramientas modernas que respeten la esencia del desarrollo web tradicional.

---

## 🎯 ¿Por qué WebAssembly?

WebAssembly (Wasm) es un formato de código binario diseñado para ejecutarse en navegadores web con alto rendimiento. Permite utilizar lenguajes como C, C++ o Rust dentro del navegador.

Fue creado en colaboración por ingenieros de:

* Mozilla
* Google
* Microsoft
* Apple

Es un tema moderno, relevante y técnicamente interesante dentro del ecosistema web actual.

---

# 🛠️ Stack Tecnológico

Aunque en la materia se trabaja HTML, CSS y JavaScript puro, este proyecto utiliza herramientas modernas que respetan los fundamentos.

## 🚀 Astro

Astro es un framework enfocado en sitios estáticos y contenido.
Se eligió porque:

* Permite escribir código muy cercano a HTML puro.
* Facilita la reutilización de componentes.
* Mantiene simplicidad (no es un framework pesado como React o Next).
* Genera sitios altamente optimizados.

Astro permite aplicar buenas prácticas modernas sin perder la comprensión de la estructura HTML tradicional.

---

## 🎨 Tailwind CSS

Tailwind CSS es un framework CSS utility-first.

Se eligió porque:

* Permite estilos rápidos y consistentes.
* Reduce la escritura de CSS manual.
* Facilita diseño moderno y responsivo.
* Mejora productividad sin sacrificar control.

---

## 🧩 Preline UI

Preline es una librería de componentes basada en Tailwind.

Se utiliza para:

* Componentes interactivos
* Mejorar la estética
* Agilizar el desarrollo visual

---

## 🔧 Git

Git se utiliza para:

* Control de versiones
* Manejo de ramas
* Seguimiento de cambios
* Buenas prácticas de desarrollo

---

# 📂 Estructura General del Proyecto

```
03-primera-entrega-webassembly/
│
├── src/
│   ├── pages/
│   │   ├── index.astro
│   │   ├── desarrolladores.astro
│   │   └── alternativas.astro
│   │
│   ├── components/
│   └── assets/
│
├── public/
├── package.json
└── README.md
```

---

# 🖥️ Instalación y Ejecución Local

## 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/usuario/03-primera-entrega-webassembly.git
cd 03-primera-entrega-webassembly
```

## 2️⃣ Instalar dependencias

```bash
npm install
```

## 3️⃣ Ejecutar en modo desarrollo

```bash
npm run dev
```

El proyecto estará disponible en:

```
http://localhost:4321
```

---

## 📦 Construcción para producción

```bash
npm run build
```

## 👀 Vista previa del build

```bash
npm run preview
```

---

# ☁️ Despliegue

El proyecto está preparado para desplegarse en plataformas como:

* Vercel
* Netlify

Al ser un sitio estático generado con Astro, el despliegue es directo y sin configuraciones complejas.

---

# 📚 Contenido del Sitio

## 🏠 Página Principal

* Historia de WebAssembly
* Contexto y evolución
* Imágenes explicativas
* Video introductorio

## 👨‍💻 Página de Desarrolladores

* Empresas involucradas
* Objetivo del proyecto Wasm
* Impacto en la industria

## 🔄 Página de Alternativas

Comparación con:

* JavaScript
* asm.js
* Otras tecnologías de ejecución web

---

# 🎓 Enfoque Académico

Aunque se utilizan herramientas modernas, este proyecto:

* Mantiene estructura semántica HTML.
* Aplica correctamente etiquetas vistas en clase.
* Implementa estilos coherentes y organizados.
* Integra contenido multimedia.
* Respeta la arquitectura multipágina solicitada.

El uso de Astro y Tailwind no reemplaza los fundamentos, sino que los potencia.

---

# 📌 Scripts Disponibles

```json
"scripts": {
  "dev": "astro dev",
  "build": "astro build",
  "preview": "astro preview",
  "astro": "astro"
}
```

---

# 📖 Dependencias Principales

```json
"astro": "^5.17.1",
"tailwindcss": "^4.2.1",
"@tailwindcss/vite": "^4.2.1",
"preline": "^4.1.2"
```

---

# 👨‍🎓 Autor

Alejandro Alomia
Estudiante – Fundamentos Web
Universidad (Primera Entrega – 2026)

---

# 🧠 Reflexión Técnica

Este proyecto demuestra que es posible aplicar fundamentos clásicos del desarrollo web utilizando herramientas modernas sin perder claridad estructural ni comprensión técnica.

Se priorizó:

* Organización
* Escalabilidad
* Claridad semántica
* Buenas prácticas
* Diseño moderno y responsivo

---

Si deseas extender el proyecto, puedes:

* Agregar ejemplos prácticos de WebAssembly
* Integrar un pequeño módulo Wasm
* Añadir comparativas técnicas más profundas
* Incorporar métricas de rendimiento

---

**Primera Entrega – Fundamentos Web – 2026**
