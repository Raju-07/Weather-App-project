# 🌦️ Know Weather

A desktop weather application built with Python and CustomTkinter that provides real-time weather information for any city using the OpenWeatherMap API.

## 📖 Overview

Know Weather is a graphical desktop application that allows users to search for weather conditions in any city around the world. The application fetches real-time weather data from the OpenWeatherMap API and presents it through an intuitive and visually appealing CustomTkinter interface.

The application displays essential weather information such as temperature, humidity, pressure, wind speed, sunrise time, sunset time, and weather conditions along with corresponding weather icons.

---

## ✨ Features

* 🔍 Search weather by city name
* 🌡️ Real-time temperature information
* 🤗 Feels-like temperature display
* 💧 Humidity monitoring
* 🌬️ Wind speed information
* 📈 Atmospheric pressure details
* 🌅 Sunrise time display
* 🌇 Sunset time display
* 🌍 Country identification
* 📅 Current date and weekday display
* 🎨 Dynamic weather condition icons
* ⚠️ Error handling for invalid city names
* 🌙 Modern dark-themed user interface

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Libraries

* CustomTkinter
* Requests
* Pillow (PIL)
* Tkinter
* Datetime

### API

* OpenWeatherMap API

---

## 📊 Weather Information Retrieved

The application displays the following real-time weather metrics:

* Temperature (°C)
* Feels Like Temperature (°C)
* Weather Condition
* Humidity (%)
* Atmospheric Pressure (mbar)
* Wind Speed
* Sunrise Time
* Sunset Time
* Country
* City Name

---

## 🖼️ Supported Weather Conditions

The application dynamically updates icons and labels based on weather conditions:

* Clear
* Clouds
* Mist
* Haze
* Rain
* Drizzle
* Thunderstorm
* Snow
* Fog
* Dust
* Overcast

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/raju-07/weather-application.git
cd weather-application
```

### Install Dependencies

```bash
pip install customtkinter
pip install requests
pip install pillow
```

Or

```bash
pip install -r requirements.txt
```

---

## 🔑 API Configuration

1. Create an account at OpenWeatherMap.
2. Generate an API key.
3. Open the source code.
4. Replace:

```python
api_key = "Enter Your API Here:"
```

with:

```python
api_key = "YOUR_API_KEY"
```

---

## ▶️ Running the Application

```bash
python main.py
```

---

## 📂 Project Structure

```text
Know-Weather/
│
├── main.py
├── Search.png
├── weather.png
├── location.png
├── temperature.png
├── humidity.png
├── wind_speed.png
├── sunrise.png
├── sunset.png
├── world.png
│
├── clear.png
├── clouds.png
├── mist.png
├── haze.png
├── rain.png
├── drizzle.png
├── thunderstorm.png
├── snow.png
├── fog.png
├── dust.png
├── overcast.png
│
└── README.md
```

---

## 💡 Future Improvements

* 5-Day Weather Forecast
* Hourly Weather Forecast
* Automatic Location Detection
* Weather Alerts and Notifications
* Multiple Temperature Units (°C / °F)
* Weather History Tracking
* Improved Error Handling
* API Response Caching

---


## 🎯 Learning Outcomes

Through this project, I gained hands-on experience with:

* API Integration using Python
* GUI Development with CustomTkinter
* JSON Data Processing
* Error Handling
* Working with External Services
* Real-Time Data Visualization
* Desktop Application Development

---

## 👨‍💻 Author

Raju Yadav

GitHub: https://github.com/raju-07

LinkedIn: https://linkedin.com/in/rajuyadav07
