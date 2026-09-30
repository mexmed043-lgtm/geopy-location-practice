# GeoPy Location Practice

A simple Python project for converting geographic coordinates (latitude and longitude) into a readable location address using GeoPy and OpenStreetMap's Nominatim service.

## What It Does

The program takes:

* Latitude
* Longitude

and uses reverse geocoding to find the corresponding location address.

## How It Works

1. `Nominatim` is imported from `geopy.geocoders`.
2. The `get_location_name()` function receives latitude and longitude.
3. `Nominatim` performs reverse geocoding.
4. The coordinates are converted into a location address.
5. The address is printed to the console.

## Example

```python
print(get_location_name(**.****, **.****))
```

The coordinates can be replaced with your own latitude and longitude values.

## Technologies

* Python
* GeoPy
* Nominatim
* OpenStreetMap

## Purpose

This project was created for learning and practicing reverse geocoding and working with geographic coordinates in Python.
