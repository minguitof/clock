# 🕑 Analog Weather Clock

An app built with **Vue 3 + Vite** that displays an **animated analog clock** along with the **current weather status**, enhanced with visual animations that reflect the weather conditions. 🌤️🌧️❄️

---

## ✨ Characteristics

- ⏰ Real-time analog clock (animated hands).
- 🌦️ Integration with [WeatherAPI](https://www.weatherapi.com/) to display:
  - Current city
  - Temperature (°C)
  - Weather condition
- 🎨 Dynamic animations: sun, rain, clouds...
- 🌈 Weather-based adaptive background (with smooth transitions).
- 🛠️ Optional devtools to manually force the background in development mode.

---

## 🚀 Preview

![preview](/Front/public/preview.jpeg) <!-- Puedes crear un screenshot del proyecto y guardarlo ahí -->

---

## 📽️ Demo on YouTube
[![See demo on YouTube](https://img.youtube.com/vi/g9TqSqyy5-g/hqdefault.jpg)](https://youtu.be/g9TqSqyy5-g)

## 📦 Facility

```bash
# Clone the project
git clone https://github.com/minguitof/clock.git
cd Front
```

## Install dependencies
npm install

## 🔐 API Key Configuration

- Sign up at weatherapi.com.
- Get your free API Key.
- Create a .env file in the project root:

```bash
VITE_API_KEY=TU_API_KEY_AQUÍ
```

## 🧪 Development mode

```bash
npm run dev
```

This opens the app at http://localhost:5173.

In development mode, you can also test other backgrounds with the following console command:

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

## 🔧 Technologies used

- Vue 3 + Vite
- Pure CSS for animations
- Weather API for weather data
- Vue's Composition API and ref, computed, and onMounted

## 📸 Credits / Inspiration

- Clock design based on minimalist ideas using CSS
- Dynamic weather inspired by apps like Weather Widget and iOS Weather App

## ✅ Future improvements (ideas)

- Add automatic geolocation (with navigator.geolocation)
- Animations for snow, storms, or fog
- Multilingual support
- Custom dark/light mode

## 📄 License

- MIT

---

Crafted with 💙 from Medellín

---