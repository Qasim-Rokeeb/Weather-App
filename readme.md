
# ⛅ Weather App – Day 26 of 30 Days of JavaScript

A responsive **weather app** built with **HTML**, **CSS**, and **JavaScript** that fetches real-time weather data from the **OpenWeatherMap API** based on the city input by the user.

---

## ✨ Features

- 🔍 Search weather by city name
- 🌡️ Shows temperature, humidity, and wind speed
- 🌤️ Displays weather icon based on conditions (Clear, Clouds, Rain, etc.)
- ⚠️ Displays an error message for invalid city names
- 📱 Responsive and modern card UI

---

## 📸 Preview

Here’s a look at the Weather App:

![App Preview](https://raw.githubusercontent.com/Qasim-Rokeeb/Weather-App/main/screenshot.png)

---

## 🌐 Live Demo

🔗 [View Live Project](https://qasim-rokeeb.github.io/Weather-App)

---

## 🧱 Built With

- **HTML5** – Markup structure
- **CSS3** – Styling, gradients, layout
- **JavaScript (ES6)** – API calls, DOM manipulation
- **OpenWeatherMap API** – Live weather data

---

## 🗂️ Project Structure

```
Weather-App/
├── index.html           # Main HTML file
├── style.css            # App styling
├── script.js            # Weather fetching logic
├── images/
│   ├── search.png
│   ├── rain.png
│   ├── clouds.png
│   ├── clear.png
│   ├── drizzle.png
│   ├── mist.png
│   └── humidity.png, wind.png
├── screenshot.png       # Screenshot for preview
└── README.md
```

---

## ⚙️ How It Works

1. User enters a city name and clicks the **search** button.
2. App sends a request to the **OpenWeatherMap API** with that city.
3. On success:
   - Shows temperature, city name, humidity, and wind speed.
   - Displays an appropriate weather icon.
4. On error (e.g. invalid city), shows an error message.

```js
const response = await fetch(apiUrl + city + `&appid=${apiKey}`);
if (response.status == 404) {
  showError();
} else {
  updateWeatherInfo(data);
}
```

---

## 🧠 What I Learned

- Using `fetch()` and `async/await` to work with APIs
- Handling API errors gracefully
- Dynamically updating DOM elements with live data
- Working with API keys and URL query strings
- Using conditionals to handle multiple weather types

---

## 📝 Notes

For your own project, you should get your own API keys using environment variables or a backend service.

---

## 📅 Challenge

This is **Day 26** of my **30 Days of JavaScript** challenge.  
Follow my journey on Twitter:

🐦 [@qasimrokeeb](https://x.com/qasimrokeeb)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
````

