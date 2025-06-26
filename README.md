<p align="center">
  <!-- App avatar/logo image (replace path as needed) -->
  <img src="images/weather-app-logo.png" alt="Weather App Logo" width="110" height="110" style="border-radius: 18px; margin-bottom: 16px;"/>
</p>

# ⛅ Weather App

A sleek and fully responsive **Weather App** that empowers users to seamlessly search for and view real-time weather conditions for any city worldwide using the **OpenWeatherMap API**. This project is crafted with **HTML**, **CSS**, and **JavaScript**, featuring a modern, user-friendly UI, dynamic weather icons, live data fetching, and a mobile-first design that adapts elegantly to any device.

---

## 📸 App Preview

<p align="center">
  <img src="https://github.com/user-attachments/assets/d345ba05-5029-4f91-90b9-40cfd42a3334" alt="Weather App Screenshot 1" width="380" style="margin: 0 8px 12px 0; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.08);"/>
  <img src="https://github.com/user-attachments/assets/909c1f55-81b3-44b8-9b87-b6a7bdb114b8" alt="Weather App Screenshot 2" width="380" style="margin: 0 8px 12px 0; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.08);"/>
</p>

---

## 🌟 Features

- 🔍 **City Search:** Instantly search for current weather in any city worldwide.
- 📍 **Location-based Weather:** (Optional) Get weather for your current location using the Geolocation API.
- 🌡️ **Live Weather Details:** Displays temperature, humidity, wind speed, pressure, and weather description.
- 🌈 **Dynamic Weather Icons:** Visually appealing icons and backgrounds that adjust based on real-time weather conditions.
- 🕒 **Local Time & Date:** Shows the local time and date of the searched city.
- 🔄 **Real-time Data:** Fetches up-to-date weather data from the OpenWeatherMap API.
- 📱 **Responsive Design:** Clean, mobile-friendly interface with smooth transitions and optimized layouts for all devices.
- 🧪 **Error Handling:** Friendly error messages for invalid city names, connection problems, or API errors.
- 🌓 **Dark/Light Mode:** (Optional/Future) Support for theme switching for comfortable viewing.
- 🗺️ **Country Flags:** (Optional) Display city’s country flag next to city name.

---

## 🛠️ Technologies Used

| Technology           | Purpose                                      |
|----------------------|----------------------------------------------|
| **HTML5**            | Semantic markup and structure                |
| **CSS3**             | Modern styling, Flexbox/Grid, animations     |
| **JavaScript (ES6+)**| DOM manipulation, API integration, logic     |
| **OpenWeatherMap API** | Real-time weather data retrieval           |
| **Geolocation API**  | (Optional) Retrieve user’s current location  |
| **FontAwesome**      | (Optional) Weather and UI icons              |

---

## 🔑 API Integration

This app utilizes the **OpenWeatherMap API** for up-to-date weather information.  
You’ll need a free API key from [OpenWeatherMap](https://openweathermap.org/api).

**How to add your API Key:**
1. Sign up and generate your API key.
2. Replace the placeholder (`YOUR_API_KEY`) in the code with your actual key.
3. Keep your API key secure and avoid exposing it in public repositories.

---

## 🌐 How It Works

1. **Enter City Name:** User enters a city and clicks "Search" (or presses Enter).
2. **API Request:** The app sends a request to the OpenWeatherMap API with the city name.
3. **Data Processing:** The response is parsed to extract temperature, humidity, wind speed, weather description, and icon.
4. **Dynamic Display:** Weather info is dynamically rendered in the UI with icons, colors, and backgrounds matching the weather.
5. **Responsive UI:** The layout adapts for desktop, tablet, and mobile users.
6. **Error Handling:** Invalid city names, network errors, or empty input are managed gracefully with user-friendly messages.

---

## 📱 Responsiveness

This Weather App is designed with a **mobile-first approach** using CSS Flexbox and media queries.  
- Looks and works great across all devices: smartphones, tablets, and desktops.
- Touch-friendly buttons and input.
- Adaptive font sizes and layouts for best usability.

---

## 🔮 Future Enhancements

- 📍 **Use My Location:** Fetch weather for your current location via Geolocation API.
- 🕒 **5-Day/Hourly Forecast:** Support for extended and detailed forecasts.
- 🌓 **Dark Mode:** Toggle between light and dark themes.
- 🌐 **Multi-Unit & Multi-Language:** Celsius/Fahrenheit toggle, support for multiple languages.
- 🧪 **UI Improvements:** Animated backgrounds, additional weather metrics (UV index, air quality).
- 🔔 **Weather Alerts:** Push notifications for severe weather (if supported by API).
- 💾 **Search History:** Remember recently searched cities for quick access.

---

## 🧑‍💻 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YourUsername/weather-app.git
   ```
2. **Add your OpenWeatherMap API key** in the script (`YOUR_API_KEY`).
3. **Open `index.html`** in your browser to use the app.

---

## 🙋‍♀️ Author

**Created by Rakhi Yadav**  
If you have ideas, suggestions, or want to contribute, feel free to [open an issue](https://github.com/YourUsername/weather-app/issues) or submit a pull request!

---

<p align="center">
  <b>Thanks for checking out the Weather App!</b><br>
  <i>Made with ❤️ and JavaScript.</i>
</p>
