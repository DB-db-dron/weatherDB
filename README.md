# [weatherDB](https://weatherdbi.herokuapp.com)
Get current weather, **daily forecast for 7 days** and weather icons for your city. **No authentication or API key required**... **Simple, easy and free** weather API.<br><br>
Our mission is to provide free, good quality weather data to anyone, anywhere.

<br><br><br>
## Useful Links
- Find us on [**Google**](https://www.google.com/search?q=site%3Aweatherdbi.herokuapp.com), [Bing](https://www.bing.com/search?q=site%3Aweatherdbi.herokuapp.com), [Yahoo](https://search.yahoo.com/search?p=site:weatherdbi.herokuapp.com)
- [Home page](https://weatherdbi.herokuapp.com)
- [Documentation page](https://weatherdbi.herokuapp.com/documentation/v1)
- [Release Notes](https://weatherdbi.herokuapp.com/release-notes)

<br><br><br>
## We are recognized
- [Programmable Web - Daily API round-up](https://www.programmableweb.com/news/daily-api-roundup-bauen-weatherdb-traqo-nextform/brief/2022/01/30#:~:text=weatherdb%20API) (Follow us on Programmable Web to appreciate our effort)
- [Programmable Web - Top APIs and Mashups](https://www.programmableweb.com/category/top-apis#:~:text=weatherDB)
- [Mixed Analytics - Big List of Free and Open Public APIs](https://mixedanalytics.com/blog/list-actually-free-open-no-auth-needed-apis/#:~:text=weatherDB)

<br><br><br>
## API Endpoint
```
https://weatherdbi.herokuapp.com/data/weather/{location}
```
Replace `{location}` with the required location. <br>
For example: london, newyork, us, papuanewguinea, sanmarino, elsalvador

<br><br><br>
## Response and Error
**GET request with valid query**
```
https://weatherdbi.herokuapp.com/data/weather/london
```
**Response:**
See response: https://weatherdbi.herokuapp.com/data/weather/london

<br><br>
**GET request with invalid query**
```
https://weatherdbi.herokuapp.com/data/weather/hello
```
**Error Response:**
```json
{
    "status": "fail",
    "message": "invalid query",
    "query": "hello"
}
```

<br><br><br>
## Upcomming features
- hourly temperature forecasts
- precipitation forecast
- historical data on specified location

<br><br><br>
## Support Us
If you like our idea, please support us by sharing words about our api with others. Write about us in your blog and create youtube tutorial using our api. Don't forget to give us a star on GitHub. **Your support is our reward and our source of enthusiasm and encouragement**

<br><br><br>
## Contact us
Mail us for feature requests, improvement, bug, help, ect... Please tell us if you want us to provide any other free easy-to-use API services<br>
Email: communication.with.users@gmail.com
