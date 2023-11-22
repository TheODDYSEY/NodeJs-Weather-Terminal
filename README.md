# Weather App Node.js Script

This Node.js script utilizes the OpenWeatherMap API to fetch and display current weather information for a given location or postal code. Users are prompted to input a location, and the script makes an API request to retrieve weather data.

## Prerequisites

Before running the script, ensure you have the following:

- Node.js installed on your machine.
- OpenWeatherMap API key. You can obtain one by signing up on [OpenWeatherMap](https://openweathermap.org/).

## Setup

1. **Clone the Repository:**
   ```bash
   https://github.com/TheODDYSEY/NodeJs-Weather-Terminal
   ```

2. **Install Dependencies:**
   Navigate to the project directory and install the required dependencies.
   ```bash
   cd your-repository
   npm install
   ```

3. **Set Up Environment Variables:**
   Create a `.env` file in the project directory and add your OpenWeatherMap API key.
   ```
   WEATHER_APP_KEY=your_api_key
   ```

## How to Use

1. **Run the Script:**
   Execute the script in your terminal.
   ```bash
   node weather-app.js
   ```

2. **Enter Location or Postal Code:**
   The script will prompt you to enter a location or postal code. Provide the required input and press Enter.

3. **View Weather Information:**
   The script will make an API request to OpenWeatherMap, and upon success, it will display the current temperature in Fahrenheit and the date and time of the weather report.

4. **Explore Further:**
   Feel free to modify the script or extend its functionality based on your requirements. You can customize the output, add more features, or integrate it into other projects.
