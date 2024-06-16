# Kraftshala Weather App

## Overview

This weather application is developed as part of Kraftshala's selection process for the Frontend Developer intern position. The app fetches real-time weather data from the Open Weather API based on user input and displays it in a user-friendly and visually appealing interface. Additionally, it includes a feature to toggle between dark mode and light mode.

## Features

- Current weather information (location, temperature, date, and time)
- Search functionality for fetching weather data of different cities
- Responsive design for desktop, tablet, and mobile devices
- Dark mode and light mode toggle
- Additional weather details: humidity, wind speed, and weather description (bonus)
-  The application currently support multiple locations simultaneously 
- Clean, readable, and maintainable code with comments and documentation

## Technologies Used

- HTML, CSS, JavaScript
- React.js (preferred framework)
- Open Weather API for fetching weather data

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/kraftshala-weather-app.git
    ```

2. Navigate to the project directory:
    ```bash
    cd kraftshala-weather-app
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

4. Create a `.env` file in the root directory and add your Open Weather API key:
    ```bash
    REACT_APP_WEATHER_API_KEY=your_api_key_here
    ```

5. Start the development server:
    ```bash
    npm start
    ```

6. Open your browser and go to `http://localhost:3000` to see the app in action.

## Usage

1. Enter a city name or zip code in the search bar and hit enter or click the search button.
2. The app will display the current weather conditions for the entered location.
3. Toggle between dark mode and light mode using the switch at the top right corner.

## Approach and Design

- **UI Design**: The interface is designed to be clean and intuitive, with a focus on ease of use.
- **Responsive Design**: The layout adjusts to different screen sizes, ensuring a good user experience on desktops, tablets, and mobile devices.
- **Dark Mode**: Implemented using CSS variables and a JavaScript toggle function to switch between dark and light themes.
- **API Integration**: Weather data is fetched from the Open Weather API using Axios. Error handling is implemented to provide feedback for invalid inputs or connection issues.
- **Code Quality**: The project structure follows best practices for React applications. Code is modular, with reusable components and proper commenting.

## Known Issues or Limitations

- There may be a slight delay in fetching data from the API depending on network conditions.


## Submission

- GitHub Repository: [GitHub Repo Link]((https://github.com/shivathota9/Kraftshala_weather_application.git))

## Deploying

-Deploy link: (https://kraftshalaweatherapplication.netlify.app)

