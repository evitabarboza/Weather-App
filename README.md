# Weather App Using OpenWeatherMap API

This project is a simple weather app that allows users to search for weather information based on a city name. The app fetches data from the OpenWeatherMap API and displays the current temperature, humidity, and wind speed. Additionally, it shows a weather icon corresponding to the current weather conditions.

## Features

- Search for weather by city name.
- Displays the current temperature, humidity, and wind speed.
- Shows weather-related icons (e.g., rain, clouds, clear sky).
- Handles invalid city names gracefully by displaying an error message.

## Technologies Used

- **HTML**: Structure of the weather app.
- **CSS**: Styling of the app.
- **JavaScript**: Fetching data from the OpenWeatherMap API and handling the user interactions.
- **OpenWeatherMap API**: Provides the weather data.

## Setup and Installation

Follow these steps to run the weather app on your local machine:

### 1. Clone the repository:
```bash
git clone https://github.com/evitabarboza/weather-app.git
```

### 2. Navigate to the project directory:
```bash
cd weather-app
```

### 3. Open the `index.html` file in a browser:
You can simply open the `index.html` file using any modern browser (e.g., Chrome, Firefox, Edge).

### 4. API Key:
To use the OpenWeatherMap API, you'll need to sign up for an API key.

- Go to [OpenWeatherMap](https://openweathermap.org/) and create an account.
- Once logged in, navigate to your [API keys](https://home.openweathermap.org/api_keys).
- Copy your API key and replace it in the JavaScript file:
  ```javascript
  const apiKey = "YOUR_API_KEY";
  ```
- Make sure to replace `"YOUR_API_KEY"` in the script with your actual API key for it to work!


## File Structure

```
/weather-app
│
├── index.html            # Main HTML file
├── styles.css            # Styling for the app
├── script.js             # JavaScript file for handling logic
├── images/               # Folder containing weather icons (rain.png, clear.png, etc.)
│
└── README.md             # Project documentation
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [OpenWeatherMap API](https://openweathermap.org/)

## Contact Information

- GitHub: [evitabarboza](https://github.com/evitabarboza)
- Email: evitabarboza195@gmail.com

