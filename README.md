# 🌾 Smart Agricultural Advisor

**AI-driven decision support system for farmers with built-in API key management**

## 🚀 Quick Start (30 seconds)

```bash
cd web-app
npm install
npm start
```

Open http://localhost:3000 in your browser 🎉

## ✨ What You Get

- **🔑 API Key Management**: Secure interface to manage your API keys
- **📱 Responsive Design**: Works on desktop, tablet, and mobile  
- **🌾 Agricultural Tools**: Crop recommendations, weather analysis, market intelligence
- **🎨 Farmer-Friendly**: Clean, intuitive interface with agricultural themes
- **💾 Secure Storage**: API keys stored locally in your browser
- **⚡ Fast Performance**: Optimized React application
- **🌐 PWA Support**: Install as a mobile app

## 🔑 API Key Setup

1. **Open the app**: http://localhost:3000
2. **Click "API Keys"** in the sidebar
3. **Add your keys** for:
   - 🌤️ **Weather API** (OpenWeatherMap) - Required
   - 🌱 **SoilGrids API** (ISRIC) - Required
   - 🛰️ **Satellite Data** (Sentinel Hub) - Optional
   - 📈 **Market Data** (Commodities API) - Optional

## 📁 Project Structure

```
smart-agri-advisor/
├── web-app/           # 🌟 Complete React web application
└── README.md          # This file
```

## 🛠️ Features

- **Dashboard**: Overview and quick access to all tools
- **Crop Recommendations**: AI-powered crop suggestions
- **Weather Analysis**: Real-time weather data and forecasts
- **Market Intelligence**: Commodity prices and market trends
- **Soil Analysis**: Comprehensive soil health assessment
- **Farm Profile**: Manage your farm information

## 📚 Documentation

- **Quick Start**: This README (you are here)
- **Web App Docs**: `web-app/README.md` - Technical reference

## 🚀 Deployment

### Local Development
```bash
npm start  # http://localhost:3000
```

### Production Build
```bash
npm run build
# Deploy 'build' folder to any static hosting
```

### Docker
```bash
docker build -t smart-agri-web .
docker run -p 3000:80 smart-agri-web
```

---

**🌾 Built with ❤️ for farmers worldwide**
