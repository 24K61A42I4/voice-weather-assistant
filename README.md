# Voice Weather Assistant

A Python weather application that retrieves current weather information for an Indian city or village using the OpenWeatherMap API and converts the report to speech with Google Text-to-Speech (gTTS).

## Features
- Accepts a city or village name as text input
- Retrieves current weather, temperature, humidity, and wind speed
- Reads the weather report aloud using gTTS

## Requirements
- Python
- `requests`
- `gTTS`

## Setup

Install dependencies:

```bash
pip install requests gTTS
```

Set your OpenWeatherMap API key securely rather than committing it to the repository. For a local environment, set an environment variable named `OPENWEATHER_API_KEY` and load it in Python with `os.getenv("OPENWEATHER_API_KEY")`.

## Run
Run the Python script or notebook, enter a location when prompted, and listen to the generated weather report.

## Security
Do not commit API keys, `.env` files, or personal credentials.
