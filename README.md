# 🏋️ GymLog

<div align="center">

[![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?style=flat-square&logo=vercel)](https://vercel.com)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20PWA-blue?style=flat-square)](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)

*Registro de entrenamiento de gym ligero, rápido y sin backend.*

</div>

---

## 📱 Preview

<div align="center">
<img src="gimnasia.png" width="80" alt="GymLog Logo" />
</div>

GymLog es una aplicación web progresiva (PWA) diseñada para registrar tus entrenos de gym. Ligera, accesible y lista para usar sin configuración compleja.

---

## ✨ Características

| Característica | Descripción |
|----------------|-------------|
| **🔐 Autenticación** | Login con usuario y contraseña, opción recordar sesión |
| **📝 Registro** | 30+ ejercicios predefinidos por grupo muscular o crea los tuyos |
| **📊 Historial** | Tabla filtrable y ordenable por fecha, ejercicio o peso |
| **📈 Gráficos** | Evolución semanal de volumen por día |
| **📉 Estadísticas** | Sesiones, series, volumen total, ejercicios únicos |
| **🏆 PR Automático** | Badge automático cuando superas tu marca personal |
| **📥 Export CSV** | Exporta tus datos para Excel/Numbers |
| **📲 PWA** | Instálala como app nativa en Android e iOS |

---

## 🚀 Despliegue

### Opción 1: Vercel CLI

```bash
# Instalar Vercel CLI
npm i -g vercel

# Desplegar
vercel
```

### Opción 2: Vercel Dashboard

1. Ve a [vercel.com/new](https://vercel.com/new)
2. Arrastra la carpeta `pesos`
3. ¡Listo!

### Opción 3: GitHub + Vercel

Conecta tu repositorio GitHub con Vercel para deployment automático en cada push.

---

## 📲 Instalación en Móvil

### Android
1. Abre la app en Chrome
2. Menú → **Añadir a pantalla de inicio**
3. ¡Listo! Appecerá como una app más

### iOS
1. Abre la app en Safari
2. Compartir → **Añadir a pantalla de inicio**
3. ¡Listo!

---

## 🛠️ Tecnologías

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Almacenamiento**: localStorage (navegador del usuario)
- **Deployment**: Vercel (static hosting)
- **PWA**: Web App Manifest

```
pesos/
├── index.html       # Aplicación completa
├── manifest.json   # PWA manifest
├── vercel.json     # Configuración de deployment
├── gimnasio.png     # Icono de la app
├── README.md       # Este archivo
└── LICENSE         # Licencia MIT
```

---

## 🔒 Privacidad

- Los datos se almacenan **localmente** en el navegador de cada usuario
- Cada usuario tiene sus datos **completamente aislados**
- No se envía ningún dato a servidores externos
- Sin backend, sin bases de datos, sin регистрация

---

## 📄 Licencia

Este proyecto está bajo la licencia [MIT](LICENSE).

---

<div align="center">

*Hecho para gymbros, por un gymbro* 🏋️‍♂️

</div>