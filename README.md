# 🏋️ GymLog - Registra tus pesos

App web para registrar tus entrenamientos en el gym. Ligera, rápida y sin backend.

![GymLog](gimnasia.png)

## ✨ Características

- **Login seguro** - Usuario y contraseña, con opción de recordar sesión
- **Registro de ejercicios** - Selecciona de una lista predefinida o crea ejercicios personalizados
- **Seguimiento de series** - Registra reps y peso por serie
- **Historial** - Visualiza todos tus registros, filtra por ejercicio y ordena por fecha/peso
- **Gráfico semanal** - Evoluciona tu volumen de entrenamiento por día
- **Estadísticas** - Sesiones, series totales, volumen acumulado, ejercicios realizados
- **Badge PR** - Se marca automáticamente cuando superas tu máximo en un ejercicio
- **Export CSV** - Exporta todos tus datos para usar en Excel
- **PWA** - Instalable como app en Android e iOS

## 🚀 Despliegue en Vercel

```bash
# 1. Instala Vercel CLI (si no la tienes)
npm i -g vercel

# 2. Despliega
cd pesos
vercel
```

O simplemente arrastra la carpeta en [vercel.com/new](https://vercel.com/new)

## 📱 Instalación en móvil

1. Abre la app en tu navegador
2. **Android**: Menú → "Añadir a pantalla de inicio"
3. **iOS**: Compartir → "Añadir a pantalla de inicio"

## 🔧 Tecnologías

- HTML5 + CSS3 + Vanilla JS
- localStorage para persistencia de datos
- Sin backend ni dependencias externas
- PWA con manifest.json

## 📂 Estructura

```
pesos/
├── index.html      # App completa
├── manifest.json   # PWA manifest
├── vercel.json     # Config Vercel
└── gimnasio.png    # Icono/favicon
```

## 👥 Usuarios

Cada usuario tiene sus datos completamente aislados. Los datos se almacenan en el navegador del usuario (localStorage).

## 📄 Licencia

MIT