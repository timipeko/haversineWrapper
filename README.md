# haversineWrapper
A thin wrapper class that enables you to calculate the distance between two locations on Earth using the Google Maps Geolocation API and haversine.

## Example

### Calculate the distance between London and Paris
```python
from wrapper import wrapper 

w = wrapper.GmapsWrapper()
w.calculate_distance('London', 'Paris')
>> "343.55 km"  
```

## Installation
Install in the usual manner using setup.py. 
Edit your Google Cloud Services Geolocation API into wrapper.py. For more information on getting an API key click [here](https://developers.google.com/maps/documentation/javascript/get-api-key)

## Contributing

Clone the project

Install [pipenv](https://github.com/pypa/pipenv).

Run `pipenv install`
