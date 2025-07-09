
# 🌦️ Weather App with Chatbot

A responsive and visually appealing web application that displays real-time weather information based on user location and integrates a smart AI chatbot assistant powered by Google's Gemini API to answer weather-related queries.

## 🚀 Features

* 📍 **Geolocation Support:** Automatically detects user location to fetch weather data.
* 🌤 **Live Weather Data:** Displays temperature, humidity, wind speed, weather condition, and emoji icons.
* 💬 **AI Chatbot Assistant:** Gemini-powered chatbot that responds to user queries based on live weather data.
* 🖼️ **Modern UI:** Responsive design with gradients, shadows, and animations for a pleasant user experience.
* 📱 **Mobile-Friendly:** Optimized layout for smaller screens and touch devices.

## 🛠️ Tech Stack

* **HTML5** / **CSS3** / **JavaScript (ES6)**
* **OpenWeatherMap API** (for real-time weather data)
* **Google Gemini API** (for chatbot responses)
* **Geolocation API** (for user location detection)

## 📦 Setup & Usage

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/weather-chatbot-app.git
cd weather-chatbot-app
```

### 2. Replace API Keys

* Open the HTML file and replace the following placeholders with your own API keys:

```javascript
const weatherApiKey = 'YOUR_OPENWEATHERMAP_API_KEY';
const geminiApiKey = 'YOUR_GEMINI_API_KEY';
```

### 3. Open in Browser

Simply open the `index.html` file in any modern browser.

---

## 🧠 AI Chatbot Functionality

The chatbot uses the **Gemini API** to respond intelligently to queries such as:

* "What should I wear today?"
* "Is it going to rain later?"
* "Is this weather good for outdoor activities?"

It includes the real-time temperature in its prompts for more contextual answers.

---

## 📷 UI Screenshots

| Weather Card                             | Chatbot Open                        |
| ---------------------------------------- | ----------------------------------- |
| ![Weather Card](assets/weather-card.png) | ![Chatbot](assets/chatbot-open.png) |

---

## 📋 File Structure

```
weather-chatbot-app/
│
├── index.html         # Main HTML file
├── assets/            # (Optional) Images for documentation/screenshots
└── README.md          # Project documentation
```

---

## 🧩 Future Improvements

* Add voice input/output for chatbot
* Support multi-day forecast
* Store chat history in local storage
* Use service workers for offline support

---

## 🔒 Security Note

Make sure to **secure your API keys** in production. Avoid exposing keys directly in client-side code.

---

## 🙌 Acknowledgements

* [OpenWeatherMap](https://openweathermap.org/api)
* [Google AI Gemini](https://ai.google.dev/)
* [MDN Web Docs](https://developer.mozilla.org/)

---

