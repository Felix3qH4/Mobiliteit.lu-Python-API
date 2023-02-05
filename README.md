# Mobiliteit.lu-Python-API
A way to use the mobiliteit.lu API with python.
For the API documentation go to http://github.com/Felix3qH4/Mobiliteit.lu-API-documentation

## Usage
```py
import mobiliteit_api as MA

connection = MA.API(api_key="my-secret-key")

departures = connection.get_departures(station_id=1234)

stations = connection.get_location_by_coordinate(coord_lat=49.171, coord_long=6.718, radius=500)

```
