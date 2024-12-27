# weather-app

A dynamic and interactive weather application built with JavaScript, providing real-time weather updates for any location.

## Features

- Fetch real-time weather data using an API.
- Display current weather conditions, temperature, humidity, and wind speed.
- Search for weather updates by city name.
- Responsive design for desktop only. 

## Demo

Try the live demo here: (https://weather-app-lake-ten-25.vercel.app/)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/AnujGawade/weather-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd weather-app
   ```

3. Open `index.html` in your web browser:

   ```bash
   open index.html
   ```

## How to Use

1. Open the application in your browser.
2. Enter a city name in the search bar and click the "Search" button.
3. View the current weather conditions for the specified city.
4. Optionally, refresh the page or search for another city.

## Technologies Used

- HTML
- CSS
- JavaScript
- Weather API 

## File Structure

```
.
├── index.html   # Main HTML file
├── style.css    # Styling for the application
├── script.js    # JavaScript logic for fetching and displaying weather data
└── README.md    # Project documentation
```

## API Setup

1. Sign up for a free API key from your chosen weather API provider (e.g., OpenWeatherMap).
2. Replace the placeholder API key in `script.js` with your actual API key:

   ```javascript
   const apiKey = 'YOUR_API_KEY_HERE';
   ```

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature-name
   ```

3. Commit your changes:

   ```bash
   git commit -m "Add your message here"
   ```

4. Push to the branch:

   ```bash
   git push origin feature-name
   ```

5. Open a pull request.

## Acknowledgments

- Weather data provided by [OpenWeatherMap].
- Built as a learning project to enhance JavaScript and API integration skills.
