# ISS Tracker Using API

This project tracks the current location of the International Space Station (ISS) using APIs and displays real-time data in a graphical format with the help of the `turtle` module in Python.

## Features

- Displays real-time position of the ISS on a world map.
- Shows the number and names of astronauts aboard the ISS.
- Displays your current geographic coordinates.
- Real-time ISS tracking updates every 5 seconds.

## Requirements

- Python 3.x
- `geocoder` library (for geolocation)
- `turtle` module (for graphical display)
- `urllib` and `json` (for fetching API data)

## Installation

1.  Clone the repository:

    ```bash
    git clone [https://github.com/azeemk210/iss-tracker-using-api.git](https://github.com/azeemk210/iss-tracker-using-api.git)
    ```

2.  Install the required Python libraries:

    ```bash
    pip install geocoder
    ```

3.  Download or create the following images for the graphical display:

    -   `images/map.gif`: A world map in `.gif` format.
    -   `images/iss.gif`: A `.gif` icon representing the ISS.

4.  Run the Python script:

    ```bash
    python iss_tracker.py
    ```

## How it Works

The script fetches the current location of the ISS using the API endpoint `http://api.open-notify.org/iss-now.json`.

It also fetches the number and names of astronauts aboard the ISS from `http://api.open-notify.org/astros.json`.

It updates your current latitude and longitude using the `geocoder` API based on your IP address.

The script then displays this information in a text file `iss.txt` and opens it in the browser.

The `turtle` graphics window shows a world map, with the ISS icon moving in real-time as the ISS orbits the Earth.

## Contribution

Feel free to fork this repository, make changes, and submit pull requests.