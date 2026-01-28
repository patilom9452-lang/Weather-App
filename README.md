# 🌤️ Weather App

A simple and responsive **Weather Application** built using **HTML, CSS, and JavaScript** that allows users to search for real-time weather information of any city. The application fetches live data from the **OpenWeatherMap API** and displays weather conditions in a clean and user-friendly interface.

---

## 🚀 Features

* 🔍 Search weather by city name
* 🌡️ Displays real-time temperature (°C)
* 💧 Shows humidity level
* 🌬️ Displays wind speed
* 🌦️ Dynamic weather icons based on conditions (Clouds, Rain, Clear, Mist, etc.)
* ⚡ Fast and asynchronous API data fetching
* 📱 Responsive UI design

---

## 🛠️ Tech Stack

* **HTML** – Application structure
* **CSS** – Styling and layout
* **JavaScript (ES6)** – Logic, DOM manipulation, API integration
* **OpenWeatherMap API** – Real-time weather data

---

## 📂 Project Structure

```
weather-app/
│
├── index.html
├── style.css
├── images/
│   ├── clear.png
│   ├── clouds.png
│   ├── drizzle.png
│   ├── mist.png
│   ├── rain.png
│   ├── humidity.png
│   ├── wind.png
│   └── search.png
└── README.md
```

---

## ▶️ How to Run the Project Locally

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```
2. Navigate to the project folder
3. Get a free API key from **OpenWeatherMap**

   * [https://openweathermap.org/api](https://openweathermap.org/api)
4. Open `index.html` and replace the API key:

   ```js
   const apiKey = "YOUR_API_KEY";
   ```
5. Save the file and open `index.html` in your browser

---

## ✅ Implementation Details

* Used **Fetch API** for making asynchronous HTTP requests
* Implemented **DOM manipulation** to dynamically update weather details
* Added **basic input validation and error handling** for invalid city names and API errors
* Ensured proper frontend logic separation for readability and maintainability

---

## 📌 Future Enhancements

* 🌍 Location-based weather using GPS
* 📆 5-day weather forecast
* 🌗 Dark / Light mode
* 🔄 Celsius ↔ Fahrenheit toggle
* 🚫 Improved UI-based error messages

---

## 👨‍💻 Author

**Om Patil**

If you find this project helpful, feel free to ⭐ the repository!
