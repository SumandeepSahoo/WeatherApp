## 🌦️ Watch Out Weather – React Weather App
A clean, responsive weather application built using React.js and Vite. Users can search for any city and get real-time weather details like temperature, humidity, and general conditions. Perfect for learning API integration, state management, and modular React development.


## 🚀 Features
```
🔍 Search weather by city

🌡️ Displays current temperature, min/max, feels-like

💧 Shows humidity and weather condition (e.g., clear, haze)

🔁 Dynamic updates via React state

📦 Clean modular component structure

⚡ Fast development with Vite

🎨 Responsive, lightweight UI
```
---

## 🛠️ Tech Stack
1. Layer	Technology

2. Frontend	React.js (via Vite)

3. Styling	CSS (modular)

4. API (assumed)	OpenWeatherMap or similar

5. State Mgmt	React Hooks (useState)

---

## 📁 Project Structure
```
mini-project-react/
├── public/
├── src/
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   ├── main.jsx
│   ├── WeatherApp.jsx
│   ├── SearchBox.jsx
│   ├── SearchBox.css
│   ├── InfoBox.jsx
│   ├── InfoBox.css
│   └── assets/
│       └── react.svg
├── index.html
├── vite.config.js
├── package.json
└── README.md
```
---

## 🚀 How to Run the Project
1. Clone the Repository
```
git clone https://github.com/sumandeep-sahoo/mini-project-react.git
cd mini-project-react
```
2. Install Dependencies
```
npm install
```
3. Start the Development Server
```
npm run dev
```
---

## 🧠 How It Works
The app initializes with a default city's weather (Wonderland)

Users type a city name into the SearchBox, which triggers an API call

The fetched data is passed to InfoBox via props to display the weather

React’s useState manages and updates weather data in real-time

Vite ensures fast hot-reloading during development

