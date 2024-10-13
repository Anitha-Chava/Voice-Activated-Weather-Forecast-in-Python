# Voice-Activated Weather Forecast in Python

This is a Python script that uses voice commands to fetch real-time weather data. The program listens for the name of a city, retrieves weather information from the OpenWeatherMap API, and reads out the weather forecast using text-to-speech.

## Features
- Converts spoken city names to text.
- Fetches real-time weather data for the specified city.
- Uses text-to-speech to read out the weather forecast.
- Error handling for unrecognized speech and API issues.

## Requirements
- Python 3.x
- `pyttsx3` for text-to-speech
- `speech_recognition` for voice input
- `requests` to fetch weather data from OpenWeatherMap API

## Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/your-username/voice-weather-forecast.git
    ```

2. Navigate to the project directory:

    ```bash
    cd voice-weather-forecast
    ```

3. Install the required dependencies:

    ```bash
    pip install pyttsx3 speechrecognition requests
    ```

4. Get your API key from [OpenWeatherMap](https://openweathermap.org/api) and replace the placeholder `API_KEY` in the script with your actual key.

## Usage

1. Run the script:

    ```bash
    python weather_forecast.py
    ```

2. The program will ask you to speak the name of the city for which you want the weather report.

3. The weather information will be fetched and read aloud.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
