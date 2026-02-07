# 🌦️ Weather App

A modern, responsive weather application built with HTML, CSS, and JavaScript using OpenWeatherMap API. Features glassmorphism design, smooth animations, and perfect mobile responsiveness.

🌟 Features
✅ Real-time weather data from OpenWeatherMap API
📱 Fully responsive - Perfect on Desktop, Tablet, Mobile
✨ Glassmorphism UI with backdrop blur effects
🎭 Smooth animations & micro-interactions
🌦️ Dynamic weather icons based on conditions
⌨️ Enter key support for search
🎨 Animated particle background
🚀 Production-ready code

🛠️ Tech Stack

Frontend: HTML5 | CSS3 | Vanilla JavaScript
API: OpenWeatherMap API
CDN: Font Awesome 6.6.0
Design: Glassmorphism | CSS Grid | Flexbox


🚀 Quick Start
Prerequisites
Get Free API Key from OpenWeatherMap
Wait 30 minutes for API key activation
Setup IAPI key from [OpenWeatherMap](https://openweathermap.org/api) or the API you are using

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Shreya-231/weather-app.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd weather-app
   ```

3. **Open `index.html` in your browser:**
   - You can double-click the `index.html` file or use a local server for better experience.

4. 🔧 Configuration
Get API Key:
Sign up at OpenWeatherMap
Copy your API key from "My API Keys"
```
Replace in script.js:
const apiKey = "YOUR_API_KEY_HERE";
```
📂 Project Structure
```
Weather-App/
├── index.html          # Main HTML file
├── style.css           # Responsive animated styles
├── script.js           # Weather API logic
├── README.md           # This file
└── screenshots/        # Demo images
```
## Usage

1. Enter the name of a city in the search bar.
2. Click the "Search" button.
3. View the current weather information displayed on the screen.

## Example Screenshot

![Weather App Screenshot](screenshot.png)

📊 API Response Example
```
{
  "name": "Mumbai",
  "main": { "temp": 28.5, "humidity": 75 },
  "weather": [{ "main": "Clouds", "description": "broken clouds" }],
  "wind": { "speed": 3.6 }
}
```
🤝 Contributing

Fork the repository
Create feature branch (git checkout -b feature/amazing-feature)
Commit changes (git commit -m 'Add amazing feature')
Push to branch (git push origin feature/amazing-feature)
Open Pull Request

## License

This project is [MIT](LICENSE) licensed.

🙏 Acknowledgments
OpenWeatherMap for free weather API
Font Awesome for beautiful icons
Design inspiration from Dribbble & Behance weather apps

⭐ Give a Star!
If you found this project helpful, please give it a star! ⭐
