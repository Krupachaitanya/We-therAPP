# ⛅ Weather Pro App



A beautiful, modern weather application built with React and Vite that provides real-time weather updates with stunning animations and a native app-like experience.

## ✨ Features

- 🌡️ Real-time weather data with detailed metrics
- 🎨 Dynamic weather-based backgrounds and animations
- 📍 Location-based weather detection
- 📱 PWA support for native app-like experience
- 🌓 Auto & manual theme switching
- 💫 Smooth animations and transitions
- 📱 Responsive design for all devices
- 🔔 Push notifications support
- 💾 Offline functionality
- 🔄 Background sync
- 📲 Haptic feedback support

## 🚀 Tech Stack

- React 18
- Vite
- TailwindCSS
- Capacitor
- Service Workers
- Modern JavaScript (ES6+)

## 🛠️ Installation

1. Clone the repository:
```bash
git clone git remote set-url origin https://github.com/Krupachaitanya/We-therAPP.git

cd We-therAPP
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your OpenWeather API key:
```env
VITE_WEATHER_API_KEY=0d4d4c4b2d9aa95461cb0c2c3f4db62a
```

4. Start the development server:
```bash
npm run dev
```

## 📱 Building for Production

### Web Build
```bash
npm run build
```

### Android Build
```bash
npm run build
npx cap add android
npx cap sync
npx cap open android
```

## 🏗️ Project Structure

```
weather-app-pro/
├── src/
│   ├── components/      # React components
│   ├── contexts/        # React contexts
│   ├── utils/          # Utility functions
│   ├── App.jsx         # Main app component
│   └── main.jsx        # Entry point
├── public/             # Static assets
├── android/           # Android platform files
└── dist/             # Production build
```

## 🎨 Key Components

- `WeatherDisplay`: Main weather information display
- `LocationManager`: Location management interface
- `Settings`: App settings and preferences
- `WeatherAnimations`: Dynamic weather-based animations
- `Navigation`: App navigation component

## 🔧 Configuration

### Capacitor Config
```json
{
  "appId": "com.chaitu.Weather",
  "appName": "Weather",
  "webDir": "dist",
  "bundledWebRuntime": false
}
```

### Tailwind Config
```javascript
module.exports = {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

## 📱 PWA Features

- Full offline support
- Background sync
- Push notifications
- App-like experience
- Home screen installation

## 🔄 API Integration

The app uses the OpenWeather API for weather data. Create an account at [OpenWeather](https://openweathermap.org/api) to get an API key.

## 🎯 Future Enhancements

- [ ] Weather forecasts
- [ ] Weather alerts
- [ ] Multiple locations
- [ ] Weather maps
- [ ] Historical weather data
- [ ] Weather widgets

## 📄 License

MIT © [Your Name]

## 👨‍💻 Author

- [Your Name]
- GitHub: [@yourusername](https://github.com/Krupachaitanya)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/krupa1030)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🙏 Acknowledgments

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [TailwindCSS](https://tailwindcss.com/)
- [Capacitor](https://capacitorjs.com/)
- [OpenWeather API](https://openweathermap.org/api)
