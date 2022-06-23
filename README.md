# Weather Report proxy server

The Weather Report proxy server is to be used with the [Weather Report web app project](https://roshnipatel.dev/weather-report/)

## Deployment with Heroku:
Link: https://weather-report-backend.herokuapp.com/

## Endpoints

| Route | Query Parameter(s) | Query Parameter(s) Description |
|--|--|--|
|`GET` `/location`| `q` | Free-form query string to search for. For `Weather Report`, this should be the city name. |
|`GET` `/weather` |`lat` & `lon`|Geographical coordinates (latitude, longitude)|
|`GET` `/location/reverse` |`lat` & `lon`| Get info of a location from its latitude, longitude|
