# ISS Tracker Using API

This project tracks the current position of the International Space Station (ISS) in real-time and displays it on a world map using Python. The script fetches live data about the ISS, astronauts aboard, and your current location, and displays it in a Turtle graphics window.

## Features

- Displays real-time position of the ISS on a world map.
- Shows the current number of astronauts aboard the ISS.
- Tracks and displays your current latitude and longitude.
- Updates the ISS position every 5 seconds.

## Requirements

Before running the script, ensure you have the following Python libraries installed:

- `geocoder`: For fetching your current latitude and longitude.
- `turtle`: For displaying the world map and ISS icon.
- `urllib`, `json`, and `time`: Standard Python libraries for fetching and parsing data.

Install the required libraries using pip:

```bash
pip install geocoder
