# Weather Application ☁️🌦️

## Overview

This Weather Application is a simple yet effective console application that retrieves the current temperature in fahrenheit for a specified city using the OpenWeatherMap API. 
Developed using .NET Core and C#, the application demonstrates my skills in API integration, data manipulation, and working with external libraries.

## Features

- **City-Based Weather Information:** Enter the name of a city, and the application fetches and displays the current weather details.
- **OpenWeatherMap API Integration:** Utilizes the OpenWeatherMap API to gather real-time weather data.
- **Data Parsing with Newtonsoft.Json:** Leverages the Newtonsoft.Json NuGet package for seamless parsing of JSON responses from the API.

## Technologies Used

- **.NET Core:** The application is built on the .NET Core framework, ensuring platform independence and scalability.
- **C#:** The primary programming language used for application logic and implementation.
- **Newtonsoft.Json NuGet Package:** Employed for efficient handling of JSON data.

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/weather-application.git
   ```

2. **Open in Visual Studio:**
   - Open the solution file (`WeatherApplication.sln`) in Visual Studio.

3. **Install Dependencies:**
   - If not automatically installed, ensure that the Newtonsoft.Json NuGet package is added.

4. **API Key Configuration:**
   - Sign up on [OpenWeatherMap](https://openweathermap.org/api) to obtain an API key.
   - Replace `YOUR_API_KEY` in the `WeatherService.cs` file with your actual API key.

5. **Run the Application:**
   - Build and run the application in Visual Studio.

6. **Enter City Name:**
   - Follow the on-screen instructions to input the desired city.

## API Key Note

Ensure that you keep your API key confidential. Consider using environment variables or a configuration manager to securely manage API keys in production.

## Resources

- **OpenWeatherMap API Documentation:** [OpenWeatherMap API](https://openweathermap.org/api)

## Acknowledgments

- Special thanks to OpenWeatherMap for providing the weather data through their API.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
