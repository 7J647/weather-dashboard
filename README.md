# weather-dashboard

## Description 

As travel slowly comes back from the effects of the global pandemic, many users will want access to quick weather statistics and data from the cities they are thinking about visiting and the most efficient user experiences will involve simply entering a city of interest and populating the data.  Key statistics of interest are current temperature, current humidity, wind speed, and UV index, with color coding of the UV index being helpful in discerning the meaning of the index number.

Simple weather icons make for easy understanding of a forecast with just a quick glance.  Since most trips and vacations include more than one day, a 5-day forecast is helpful and the simple weather icons that communicate conditions reduce the amount of time needed to absorb the information presented.

As users plan their trips they will likely have many cities searched and it is helpful to have a list of those cities in a list that they can refer to, and if they want to look back multiple times at a particular city's forecast it is beneficial for the user to be able to simply click on the name.

Users might close their browser or refresh the page and in either instance it is helpful to have the weather stats for the last city searched appear right where they were when they last left.

This project was a more in-depth study of third-party APIs with a more challenging "mining" of data from a popular weather API called OpenWeatherMap.  Moment.js was also used to incorporate dates.  The project was extremely challenging and took almost every bit of the allotted time to complete, and was completed roughly 30 minutes before the submission deadline.

I had the most trouble utilizing local storage and turning the value of previous searches into strings that could be used in the API calls.  One problem that was not resolved is the list of prior searches has no end, it continues down "forever" depending on how many searches are completed before local storage is cleared.

In addition I would have liked to have had more time for additional styling but due to the time constraints I had to go with what I had.

Finally, when viewed on the actual URL there's a "5-Day Forecast" heading that I had difficulty hiding before the first city was searched for, I had accomplished this somewhere in the process but when I added functions to load the weather data from saved searches and the last search before closing the browser, this headline came back.

### URL and Screen Shot

The URL for this website is https://7j647.github.io/weather-dashboard/

<img src ="./ScreenShot.jpg" alt= "Weather Dashboard app screen shot">

### Credits

With thanks to Coach Jonathan and his team and to Josh Furlin who greatly assisted in multiple tudor sessions.


#### License

Copyright (c) [2020] [Jeff Flynn]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

##### Badges

![badmath](https://img.shields.io/github/languages/top/nielsenjared/badmath)


###### Contributing

For other developers who would like to improve the work done on this project or offer suggestions, please feel free to do so and Slack me with your comments.
