# [weatherDB](https://weatherdbi.herokuapp.com)
Get current weather, **daily forecast for 7 days** and weather icons for your city. **No authentication or API key required**... **Simple, easy and free** weather API.<br><br>
Our mission is to provide free, good quality weather data to anyone, anywhere. [Join us today](#join-us-today)

<br><br><br>
## Useful Links
- **_Find us on_** [**_Google_**](https://www.google.com/search?q=site%3Aweatherdbi.herokuapp.com), [Bing](https://www.bing.com/search?q=site%3Aweatherdbi.herokuapp.com), [Yahoo](https://search.yahoo.com/search?p=site:weatherdbi.herokuapp.com)
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
**GET request with invalid query**: This error occurs when the specified location does not exists, weather data for that location is not available, there is a spelling error or there is any other popular name for that location.
```
https://weatherdbi.herokuapp.com/data/weather/hello
```
**Error Response:**
```json
{
    "status": "fail",
    "message": "invalid query",
    "query": "hello",
    "code": 0,
    "visit": "https://weatherdbi.herokuapp.com/documentation/v1"
}
```

<br><br>
**GET request with invalid query**: This error occurs when possible harmful characters are present in the query. To avoid this, do not put anything other than A-Z, a-z, 0-9, hyphen, comma, plus, space, &, full stop in the query.
```
https://weatherdbi.herokuapp.com/data/weather/l*)$o@nd'o%20n
```
**Error Response:**
```json
{
    "status": "fail",
    "message": "Rejected characters in query",
    "query": "l*)$o@nd'o n",
    "rejected": "*)$@'",
    "code": 1
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
Mail us for feature requests, improvement, bug, issue, help, ect...<br>
Email: **_communication.with.users@gmail.com_**<br>
You can send us a message from our website: [Talk to us Section](https://weatherdbi.herokuapp.com/#:~:text=talk%20to%20us)


<br><br><br>
## Join us today!
Want to contribute to this API? You are welcome. Send an email to **_communication.with.users@gmail.com_** mentioning your skills. We will reach out to you as soon as possible.<br>
**We are looking for _front-end developers_ with sufficient knowledge of html, css and Javascript.**
