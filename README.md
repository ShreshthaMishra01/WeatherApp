# ☀️ Weather App

A simple and responsive Weather Application built using **HTML, CSS, and JavaScript** that allows users to check real-time weather information for any city around the world.

The application uses the OpenWeatherMap API to fetch and display current weather details, including temperature, weather conditions, humidity, and wind speed.

## 🚀 Features

- **Search by City:** Enter any city name to get its current weather information.
- **Real-Time Weather Data:** Fetches updated weather information using the OpenWeatherMap API.
- **Temperature Display:** Shows the current temperature in Celsius (°C).
- **Weather Conditions:** Displays weather descriptions such as clear sky, clouds, rain, etc.
- **Humidity Information:** Shows the current humidity percentage.
- **Wind Speed:** Displays wind speed in meters per second.
- **Error Handling:** Displays appropriate messages for invalid city names or failed API requests.
- **Loading State:** Shows a loading message while fetching weather data.

## 🛠️ Technologies Used

- **HTML5** – Structure of the application.
- **CSS3** – Styling, layout, gradients, and responsive design.
- **JavaScript (ES6+)** – Application logic and asynchronous API handling.
- **OpenWeatherMap API** – Fetching real-time weather information.
- **Fetch API** – Making HTTP requests to the weather API.

## 📂 Project Structure

```text
WeatherApp/
│
├── index.html      # Main HTML structure
├── style.css       # Application styling
├── script.js       # JavaScript logic and API integration
└── README.md       # Project documentation
```

## ⚙️ How It Works

1. The user enters a city name in the search field.
2. JavaScript retrieves the city name from the input field.
3. The Fetch API sends a request to the OpenWeatherMap API.
4. The API returns weather information in JSON format.
5. JavaScript processes the response and dynamically displays:
   - City Name
   - Temperature
   - Weather Description
   - Humidity
   - Wind Speed
6. If the city is invalid or the API request fails, an error message is displayed.

## 🔑 API Integration

This project uses the **OpenWeatherMap Current Weather API**.

API Endpoint:

```text
https://api.openweathermap.org/data/2.5/weather
```

To run the project with your own API key:

1. Visit [OpenWeatherMap](https://openweathermap.org/api).
2. Create an account.
3. Generate your API key.
4. Add the API key to `script.js`.

```javascript
const API_KEY = "YOUR_API_KEY";
```

**Note:** Keep your API key private. For a publicly deployed application, use a backend server to protect API credentials.

## 💻 How to Run Locally

1. Clone this repository:

```bash
git clone YOUR_REPOSITORY_URL
```

2. Open the project folder.

3. Make sure your API key is configured in `script.js`.

4. Open `index.html` in your browser.

5. Enter a city name and click the Search button to check its weather.

## 📸 Project Preview

The application features a clean interface with:
- A gradient background.
- A centered weather search container.
- A city search input field.
- A dynamic weather information section.

## 🎯 Learning Outcomes

Through this project, I learned:

- Working with third-party APIs.
- Making asynchronous HTTP requests using `async/await`.
- Understanding JavaScript Promises and the Fetch API.
- Handling JSON responses.
- Implementing error handling using `try-catch`.
- Dynamically updating HTML content using JavaScript DOM manipulation.

## 👩‍💻 Author

**Shreshtha Mishra**

- GitHub: [ShreshthaMishra01](https://github.com/ShreshthaMishra01)
- LinkedIn: [Shreshtha Mishra](https://www.linkedin.com/in/shreshtha-mishra-263a823b)

---

## 🌐 Live Demo

[Click here to view Weather App](https://fastidious-phoenix-4e50af.netlify.app/)

⭐ If you find this project useful, consider giving it a star!