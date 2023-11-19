# US Bikeshare Data Analysis

This project analyzes bikeshare data from three US cities - Chicago, New York City, and Washington .

## Overview

The script `bikeshare.py` takes in raw input from the user to select a city, month, and day to analyze. It then imports, cleans, and analyzes the data using Pandas functions and provides statistics including:

- Most popular times of travel (month, day of week, hour of day)
- Most popular stations and trips
- Trip duration statistics
- User statistics (counts, gender, birth years)

The results of the analysis are printed to the terminal.

## Functions

### `get_filters()`

Prompts the user to specify a city, month, and day to analyze. Returns the selected filters.

### `load_data()`

Loads the data for the specified city and filters by the selected month and day.

### `time_stats()`

Displays statistics on the most frequent times of travel.

### `station_stats()`

Displays statistics on the most popular stations and trips.

### `trip_duration_stats()`

Displays statistics on the total and average trip duration.

### `user_stats()`

Displays statistics on bikeshare users.

### `display_data()`

Displays raw data upon request by the user with 5 rows at a time.

### `main()`

Runs the program to call the above functions in sequence and restart if desired.

## Usage

The program can be run as:
In terminal, navigate to the directory containing the bikeshare.py file and run the following command:

```bash
python bikeshare.py
