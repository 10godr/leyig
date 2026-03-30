# LEYIG — Instagram Follower Analyzer

Analiza tus seguidores de Instagram sin iniciar sesión. Todo se procesa en el navegador del usuario — cero datos enviados a ningún servidor.

## 🚀 Deploy en Vercel (3 pasos)

### Opción A — Vercel CLI
```bash
npm i -g vercel
vercel
```
Sigue las instrucciones. Listo.

### Opción B — GitHub + Vercel (recomendado)

1. Sube esta carpeta a un repositorio de GitHub
2. Ve a [vercel.com](https://vercel.com) → New Project
3. Importa el repositorio → Deploy

No necesitas configurar nada más. Vercel detecta automáticamente que es un sitio estático.

## 📁 Estructura del proyecto

```
leyig/
├── index.html      ← Toda la aplicación
├── vercel.json     ← Config de Vercel (headers, rutas)
├── package.json    ← Metadata del proyecto
└── README.md       ← Este archivo
```

## ⚙️ Desarrollo local

```bash
npx serve .
# Abre http://localhost:3000
```

## 🔒 Privacidad

- Sin backend
- Sin base de datos
- Sin analytics
- Sin cookies
- Los archivos JSON nunca salen del dispositivo del usuario
