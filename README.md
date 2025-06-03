# Weather App with Flask

![Python](https://img.shields.io/badge/python-3.7+-blue.svg)
![Flask](https://img.shields.io/badge/flask-2.0+-green.svg)
![OpenWeatherMap](https://img.shields.io/badge/API-OpenWeatherMap-yellow.svg)
![License](https://img.shields.io/badge/license-MIT-orange.svg)

A simple web application built with Flask that displays current weather information for any city using the OpenWeatherMap API.

## Features

- Real-time weather data for any city worldwide
- Displays:
  - Current temperature 
  - Weather conditions
  - Minimum and maximum temperatures
  - Weather icon visualization
- Responsive design
- Simple and intuitive interface

## Screenshot

![Screenshot 2025-06-01 113005](https://github.com/user-attachments/assets/b209bc43-0330-4d92-a608-451106eee49a)


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-app-flask.git
   cd weather-app-flask
Create and activate a virtual environment (recommended):

bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install dependencies:

bash
pip install flask requests
Set up your OpenWeatherMap API key:

Get a free API key from OpenWeatherMap

Replace the API key in app.py:

python
url = 'http://api.openweathermap.org/data/2.5/weather?q={city_name}&units=metric&APPID=your_api_key_here'
Usage
Run the Flask application:

bash
python app.py
Open your web browser and visit:

http://localhost:5000
Enter a city name and click "Search Now"

Project Structure
weather-app-flask/
├── app.py                # Main application file
├── templates/
│   └── index.html        # HTML template
├── static/               # (Optional) For CSS/JS files
└── README.md             # This file
Dependencies
Python 3.7+

Flask

Requests

API Reference
This application uses the OpenWeatherMap Current Weather Data API.

Contributing
Contributions are welcome! Please open an issue first to discuss what you'd like to change.

Fork the project

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

License
Distributed under the MIT License. See LICENSE for more information.

Contact
Your Name - @your_twitter - your.email@example.com

Project Link: https://github.com/your-username/weather-app-flask


### Additional recommendations:

1. **Add a screenshot**:
   - Replace the placeholder URL with an actual screenshot
   - Name it `screenshot.png` and add to your repository

2. **Create a requirements.txt**:
   ```bash
   pip freeze > requirements.txt
Add a .gitignore file with:

venv/
__pycache__/
*.pyc
.env
For better security:

Consider moving the API key to environment variables

Create a .env.example file for others to reference

Optional enhancements:

Add deployment instructions (Heroku, AWS, etc.)

Include a features roadmap

Add a demo link if deployed online
