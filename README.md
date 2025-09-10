
# 🌤️ Weather App

A simple and responsive Weather App built using **HTML**, **CSS**, and **JavaScript** that fetches real-time weather data using a public Weather API (like OpenWeatherMap or WeatherAPI).

---

## 🔍 Features

- 🌦️ Get real-time weather information by city name
- 🌡️ Displays temperature, weather description, humidity, and wind speed
- 📍 Optionally fetch weather data using geolocation
- 🌙 Dynamic weather icons and background themes
- 📱 Fully responsive design for mobile and desktop

---

## 🖼️ Preview

![Weather App Preview]
<img width="1912" height="939" alt="image" src="https://github.com/user-attachments/assets/b6891a0d-ea6c-4582-8d96-fcd4336295ef" />


## 🚀 Technologies Used

- **HTML5** – Page structure
- **CSS3** – Styling and responsiveness
- **JavaScript (ES6)** – Logic and API integration
- **Weather API** – (e.g., OpenWeatherMap or WeatherAPI)

---

## 🔧 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/weather-app.git
   cd weather-app
````

2. **Get a free API key**

   * Go to [OpenWeatherMap](https://openweathermap.org/api) or another weather API provider.
   * Sign up and generate a free API key.

3. **Configure the API key**

   * Open `script.js` or `config.js` (depending on your setup)
   * Replace `'YOUR_API_KEY'` with your actual API key:

     ```javascript
     const API_KEY = 'your_actual_api_key';
     ```

4. **Run the app**

   * Open `index.html` in your browser

---

## 🧠 How It Works

1. User enters a city name.
2. JavaScript fetches weather data using `fetch()` from the Weather API.
3. Parses the JSON response.
4. Updates the DOM with weather information.
5. Optionally uses `navigator.geolocation` to get user's current location.

---

## 📁 Project Structure

```
weather-app/
│
├── index.html         # Main HTML file
├── style.css          # App styles
├── script.js          # Main JavaScript logic
├── preview.png        # (Optional) Screenshot for README
└── README.md          # Project documentation
```

---

## 📌 Notes

* This app uses client-side JavaScript, so make sure you're aware of the limitations when exposing API keys.
* For production, consider using a backend proxy to secure API requests.


## 📬 Contact

Created by - Avi Kundu (mailto:avikundu2003@gmail.com)
GitHub: [@Avi2k03](https://github.com/Avi2k03)

Let me know if you'd like a version tailored to a specific API (like OpenWeatherMap), or want me to generate the actual `script.js` and `index.html` as well.
```
