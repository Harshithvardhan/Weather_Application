# 🌤️ Weather Application

A simple **Weather Application built using Python and Tkinter** that uses the **OpenWeatherMap API** to retrieve and display real-time weather information for a selected city.

## 📌 Overview

This project provides a simple graphical interface where users can enter a city name and retrieve its current:

* 🌦️ Weather condition
* 🌡️ Temperature
* 💧 Humidity

The application sends a request to the OpenWeatherMap API and displays the returned weather information in the GUI.

## ✨ Features

* 🌍 Search weather by city name
* 🌡️ Display temperature in Celsius
* 💧 Display humidity percentage
* 🌦️ Display current weather condition
* 🖥️ Simple Tkinter graphical interface
* ⚠️ Error handling for invalid or unavailable cities
* 🔗 Integration with OpenWeatherMap API

## 🛠️ Technologies Used

* **Python**
* **Tkinter** — GUI development
* **Requests** — API requests
* **OpenWeatherMap API** — Weather data
* **JSON** — Processing API responses

## 📂 Project Structure

```text
OIBSIP-Weather-Application/
│
├── weather_application.py
└── README.md
```

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/OIBSIP-Weather-Application.git
```

### 2. Navigate to the Project

```bash
cd OIBSIP-Weather-Application
```

### 3. Install Required Package

Install the `requests` library:

```bash
pip install requests
```

> Tkinter is normally included with standard Python installations.

## 🔑 API Configuration

This application uses the **OpenWeatherMap API**.

Open the Python file and replace:

```python
api_key = "Your API_Key"
```

with your own OpenWeatherMap API key.

The API request uses the city name, metric units, and API key to retrieve weather data.

> **Security Note:** Do not upload your personal API key publicly to GitHub. For a production project, store it in an environment variable or `.env` file.

## ▶️ How to Run

Run the following command:

```bash
python weather_application.py
```

The Weather Application window will open.

Enter a city name and click:

**Get Weather**

## 🖥️ Example

```text
Enter the City Name:

[ Visakhapatnam ]

       Get Weather

The WEATHER in Visakhapatnam is: Clear
The TEMPERATURE in Visakhapatnam is: 28°C
THE HUMIDITY in Visakhapatnam is: 70%
```

*The values above are only an example; actual weather information depends on the API response.*

## 🔄 How It Works

```text
User Enters City
       ↓
Click "Get Weather"
       ↓
Send API Request
       ↓
OpenWeatherMap API
       ↓
Receive JSON Response
       ↓
Extract Weather Data
       ↓
Display Results
```

The application checks the API response status. A successful response extracts the weather condition, temperature, and humidity.

## ⚠️ Error Handling

The application handles invalid city searches using error messages.

* **200** → Weather information is displayed.
* **404** → City not found.
* Other responses → Prompts the user to enter the correct city.

## 🖼️ User Interface

The application includes:

* City name input field
* **Get Weather** button
* Weather result display
* Error message dialogs

The interface is created using Tkinter and `ttk` widgets.

## 🎯 Learning Outcomes

Through this project, I learned:

* Python GUI development
* Working with REST APIs
* Sending HTTP requests
* Processing JSON responses
* Using API keys
* Handling API response codes
* Exception and error handling
* Building interactive desktop applications

## 🔮 Future Improvements

Possible improvements include:

* 📍 Automatic location-based weather
* 📅 5-day weather forecast
* 🌅 Sunrise and sunset information
* 💨 Wind speed and direction
* 🌧️ Weather icons
* 🌙 Dark mode
* 🔄 Automatic weather updates
* 📊 Extended weather statistics
* 🔐 Secure API key management using environment variables

## 👨‍💻 Author

**Harshith Vardhan**

* GitHub: https://github.com/Harshithvardhan
* LinkedIn: Add your LinkedIn profile here

## 📜 License

This project was developed for **educational and internship purposes** as part of the **OIBSIP Internship Program**.
