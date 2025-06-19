# 🕑 Analog Weather Clock

Una app hecha con **Vue 3 + Vite** que muestra un **reloj analógico animado** junto con el **estado actual del clima**, y lo adorna con animaciones visuales según la condición meteorológica. 🌤️🌧️❄️

---

## ✨ Características

- ⏰ Reloj analógico en tiempo real (manecillas animadas).
- 🌦️ Integración con [WeatherAPI](https://www.weatherapi.com/) para mostrar:
  - Ciudad actual
  - Temperatura (°C)
  - Condición del clima
- 🎨 Animaciones dinámicas: sol, lluvia, nubes...
- 🌈 Fondo adaptable según el clima (con transiciones suaves).
- 🛠️ Devtools opcionales para forzar el fondo manualmente en desarrollo.

---

## 🚀 Vista previa

![preview](public/preview.jpeg) <!-- Puedes crear un screenshot del proyecto y guardarlo ahí -->

---

## 📦 Instalación

```bash
# Clona el proyecto
git clone https://github.com/minguitof/clock.git
cd Front
```

## Instala dependencias
npm install

## 🔐 Configuración de API Key

- Regístrate en weatherapi.com.
- Obtén tu API Key gratuita.
- Crea un archivo .env en la raíz del proyecto:

```bash
VITE_API_KEY=TU_API_KEY_AQUÍ
```

## 🧪 Modo desarrollo

```bash
npm run dev
```

Esto abre la app en http://localhost:5173.

En modo desarrollo también puedes probar otros fondos con el siguiente comando en consola:

```bash
weatherDebug.setBackground('rainy-bg') // Cambia a 'sunny-bg', 'cloudy-bg', etc.
```

## 🗂️ Estructura del proyecto

```bash
src/
│
├── components/
│   ├── ClockAnimated.vue
│   ├── Weather.vue
│   └── WeatherAnimation.vue
│
├── composables/
│   └── useWeather.js
│
├── App.vue
└── main.js
└── style.css
```

## 🔧 Tecnologías utilizadas

- Vue 3 + Vite
- CSS puro para animaciones
- WeatherAPI para datos climáticos
- Composition API y ref, computed, onMounted de Vue

## 📸 Créditos / Inspiración

- Diseño del reloj basado en ideas minimalistas con CSS
- Clima dinámico inspirado por apps como Weather Widget y iOS Weather App

## ✅ Mejoras futuras (ideas)

- Agregar ubicación geográfica automática (con navigator.geolocation)
- Animaciones para nieve, tormenta o niebla
- Soporte multilingüe
- Modo oscuro/light personalizado

## 📄 Licencia

- MIT

---

Hecho con 💙 desde Medellín

---