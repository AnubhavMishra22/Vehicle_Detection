# Automated Parking Counter

An automated parking counter based on CCTV footages for parking spots near you.

![image](/outputs/1.jpeg)

## Getting Started

The Vehicles_detection.py is an organisation script and is supposed to be executed by the parking authorities/companies using their cctv footages as input. The algorithm counts the number of cars and calculates slots left in a given parking lot. This number is then passed on to the user through a mobile application.

### Prerequisites

The mobile application is a stand-alone apk file. No external dependencies required.
Any required dependencies for the algorithm can be installed using-

```
python install.py
```

## Running the tests
Clone the repository. Add cctv footages to be analysed into the parent directory where vehicle_detection.py exist ([some_examples](https://drive.google.com/open?id=1kayO8KoOVQkK1mucxAItKCpUVrvCgWmw)), open a terminal and execute command:

```
python Vehicles_detection.py
```

## Deployment

The end to end stack of the software is deployed in heroku. (only the application has access to the url)

## Built With

* [OpenCV](https://opencv.org/)
* [Heroku](https://www.heroku.com/home)
* [Python](https://www.python.org/)
