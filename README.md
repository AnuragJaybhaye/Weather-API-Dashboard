**Weather-API-Dashboard**

After working with static datasets, I wanted to take on a new challenge: building a dashboard that visualizes live, dynamic data. I decided to create a personal weather dashboard, seeing it as the perfect opportunity to learn how to connect to a real-time API and design a beautiful, functional interface from the ground up. 🌦️

**Step 1: Tapping into Real-Time Data via API**

The heart of this project was the data source. Instead of a CSV file, my source was a live WeatherAPI. The first step was to establish a connection in Power BI. This involved using the API endpoint, managing my private API key, and understanding the structure of the data it sent back.
The API returned data in a JSON format, which was a nested web of information. I used Power Query to parse this JSON data, navigating through its different layers to extract every key piece of information—from the current temperature and wind speed to detailed hourly forecasts and complex air quality metrics. This process was crucial for transforming raw, machine-readable data into a clean, organized table that Power BI could understand. 🔌

**Step 2: Designing a User-Centric Dashboard**

With the live data flowing, my focus shifted to design and user experience (UI/UX). I wanted to create a dashboard that was not only informative but also intuitive and visually appealing.
I chose a sleek dark mode theme to make the data points pop. I designed custom cards and used icons to give users an "at-a-glance" understanding of the current conditions. The most important features I built were:
1) Live Metrics: Shows the current temperature, visibility, wind speed, humidity, and more.
2) 7-Day Forecast: A line chart that visually displays the temperature trend for the upcoming week.
3) Air Quality Index (AQI): A dedicated section that breaks down pollutants like PM2.5, NO2, and Ozone, with a color-coded gauge (using DAX for conditional formatting) to show if the air is healthy or not. ✅
4) Dynamic Location Selector: Users can seamlessly switch between different cities like Hyderabad, Chennai, and Darjeeling to get instant updates.
    
**The Result: Data in Real-Time**
The final result is a responsive, all-in-one weather station. As of this morning, a user could see that it was 24.2 °C and misty in Hyderabad, with a 100% chance of rain today. They could also see that the air quality was "Good" with an AQI of 37, and that sunset would be at 06:46 PM. ☀️
This project was an incredible learning experience. It pushed me beyond static files and taught me the end-to-end process of working with live APIs from the initial connection and JSON parsing to designing a polished and insightful dashboard. It proves that with the right tools, we can turn the constant flow of data from the world around us into something clear, useful, and beautiful. 💡

Here is the Dashboard: 

![alt text]()
