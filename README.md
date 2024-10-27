# Weather-App
Weather Forecasting Application is one of the most common mini project in Software Development . In this article, we are going to make a Weather Forecasting Application from scratch which will tell us the weather of any location using its name . We will be covering all the steps you have to do while developing this mini project. The title of our project will be Todays Weather App.
# Approach
Create the Weather App UI Structure using the HTML elements like <div>, <h1>, <input> and <button>. Embed all the essential CDN links for Icons, Fonts, etc.
Once the structure is created, the styling properties for each element like padding, box-shadow, transition, attractive effects like hovering, etc are been applied.
In the main JavaScript file, the overall behavior of the application is been defined.
Firstly, we are specifying the API URL of OpenWeatherMap. Then we are specifying the unique API key. By defaul,t the Weather of the Pune location is been shown when the application is loaded.
Then by using the async function, we are returning the wwather of the city which is entered by the user. If the city is not valid, then an error message is been shown to the user.
Once the details are fetched, then these details are been represented in the weatherShowFn().
