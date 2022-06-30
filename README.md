# Weather App
This weather web app built with Flask and OpenWeather API displays the weather forecast for any city. I designed a simplistic UI to make it easier for the user to find the relevant information. All HTML, CSS, and Python code was written from scratch and the CSS is responsive due to the use of CSS grid, flexbox, and media queries.

## Screenshots (Desktop)
<img src="/screenshots/weather_app_desktop_forecast_page_screenshot.png">

## Screenshots (Mobile)

## Process
-  Determine key functionality of the app and design the UI in Figma. Use assets - images and icons - downloaded from Unsplash and Icons8.
-  Write the HTML for the home page and 'city' page that displays the weather forecast for a specific city. Then, style these pages to match the UI design. Make sure design is responsive.
– Set up flask server
To deploy this web app, I also learned about git and version control through Angela Yu's Python bootcamp on Udemy. I also had to learn about storing API keys as environment variables with .env and the purpose of .gitignore.
Even after deploying the app, I discovered that the web page didn't render as expected or desired on my iPhone 11 Pro. This was an issue with the responsive design so I had to address this again.  

Honestly, this was much more frustrating and complicated than I had anticipated but I learned and grew a lot as a developer by tackling each problem.
For instance, I had difficulty positioning my footer at the bottom of my page and had to refer to [this amazing resource](https://stackoverflow.com/questions/51683107/making-a-footer-stay-at-the-bottom-of-the-page-both-in-mobile-view-and-desktop-v) to adjust my CSS accordingly. I also discovered after deploying my app that the Chrome browser tools are not entirely accurate for the mobile view. My page wasn't rendering as beautifully on mobile so after some deliberation, I downloaded Responsively and this tool proved to be a godsend! 

## Reflection
This is one of the first apps I'm building from scratch in Python and therefore, it was difficult for me to add all the functionality I wanted to in a way that would ensure the UI/UX design remained seamless. If I were to do this project again, I would add an option for users to specify the country of the city they enter (if multiple countries share the same city name). I would also display the low and high temperatures for each day in the five day forecast instead of only displaying the temperature at noon. It would also be useful to enable location detection to allow the user to get more accurate weather data for their current location by using their precise coordinates instead of relying on the geocoding API provided by OpenWeather.

## Useful Resources
- [OpenWeather API Documentation](https://openweathermap.org/api/one-call-3)
- [Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [StackOverflow Post on Centering in CSS Grid](https://stackoverflow.com/questions/45536537/centering-in-css-grid)
- [Youtube video on searching blog posts with Flask](https://www.youtube.com/watch?v=kmtZTo-_gJY)
- [Article on retrieving HTML form data with Flask](https://www.geeksforgeeks.org/retrieving-html-from-data-using-flask/)
- [StackOverflow post on building Flask app search bar](https://stackoverflow.com/questions/39960942/flask-app-search-bar)
- [Article on storing API keys as environment variables](https://jonathansoma.com/lede/foundations-2019/classes/apis/keeping-api-keys-secret/)
– [StackOverflow post on storing API keys in Heroku](https://stackoverflow.com/questions/71593743/storing-api-key-in-heroku)
- []

## Image Credit
- Home page background image: https://unsplash.com/photos/2KXEb_8G5vo
- Error page desktop background image: https://unsplash.com/photos/U-Kty6HxcQc

### Icons 
- <a target="_blank" href="https://icons8.com/icon/pLiaaoa41R9n/wind">Wind</a> icon by <a target="_blank" href="https://icons8.com">Icons8</a>
- <a target="_blank" href="https://icons8.com/icon/37802/thermometer">Thermometer</a> icon by <a target="_blank" href="https://icons8.com">Icons8</a>
- <a target="_blank" href="https://icons8.com/icon/99328/clouds">Clouds</a> icon by <a target="_blank" href="https://icons8.com">Icons8</a>
- <a target="_blank" href="https://icons8.com/icon/101829/rain">Rain</a> icon by <a target="_blank" href="https://icons8.com">Icons8</a>
- <a target="_blank" href="https://icons8.com/icon/67657/fog">Fog</a> icon by <a target="_blank" href="https://icons8.com">Icons8</a>
- <a target="_blank" href="https://icons8.com/icon/hXkspV0LTEoE/snow">Snow</a> icon by <a target="_blank" href="https://icons8.com">Icons8</a>
- <a target="_blank" href="https://icons8.com/icon/G3xS4dQTvswX/rainy-weather">Rainy Weather</a> icon by <a target="_blank" href="https://icons8.com">Icons8</a>
- <a target="_blank" href="https://icons8.com/icon/101843/storm">Storm</a> icon by <a target="_blank" href="https://icons8.com">Icons8</a>
- <a target="_blank" href="https://icons8.com/icon/59878/search">Search</a> icon by <a target="_blank" href="https://icons8.com">Icons8</a>
- <a target="_blank" href="https://icons8.com/icon/39789/chevron-left">Chevron Left</a> icon by <a target="_blank" href="https://icons8.com">Icons8</a>
- <a target="_blank" href="https://icons8.com/icon/99362/summer">Summer</a> icon by <a target="_blank" href="https://icons8.com">Icons8</a>
- <a target="_blank" href="https://icons8.com/icon/akbaie9da2Be/tornado">Tornado</a> icon by <a target="_blank" href="https://icons8.com">Icons8</a>
