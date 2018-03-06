# Weather Progressive Web App

Build a Weather web app using Progressive Web App techniques. 

The app will:

Utilize and demonstrate the above principles of Progressive Web Apps.
Use live weather data.
Provide app-like interactions to allow the user to add cities.

In the HTML file, the key components will consist of:

Header with a title, and add/refresh buttons
Container for forecast cards
A forecast card template
A dialog for adding new cities
A loading indicator

In the app code (scripts/app.js), there are:

An app object that contains some of the key information necessary for the app,
The event listeners for all of the buttons in the header (add/refresh) and in the add city dialog (add/cancel),
A method to add or update forecast cards (app.updateForecastCard)
A method to get the latest weather forecast data from the Firebase Public Weather API (app.getForecast),
A method to iterate the current cards and call app.getForecast to get the latest forecast data (app.updateForecasts),
Some fake data (initialWeatherForecast) you can use to quickly test how things render.
