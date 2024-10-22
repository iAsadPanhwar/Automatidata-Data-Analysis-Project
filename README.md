# NYC Yellow Taxi Data Analysis

## Project Overview

This repository contains a step-by-step analysis of the **New York City Yellow Taxi dataset** using **Python**. The goal is to explore the data, perform cleaning, visualize key metrics, and gain insights into trip durations, fare distributions, peak hours, and more.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Prerequisites](#prerequisites)
4. [Installation](#installation)
5. [Step-by-Step Analysis](#step-by-step-analysis)
6. [Visualizations](#visualizations)
7. [Project Structure](#project-structure)
8. [Contributing](#contributing)
9. [License](#license)
10. [Acknowledgements](#acknowledgements)

## Dataset

The **New York City Yellow Taxi** dataset includes information such as:

- Pickup and dropoff locations (latitude and longitude)
- Trip duration and distance
- Fare amounts and tips
- Passenger counts
- Payment types

### Data Source

The dataset can be downloaded from the [NYC Taxi &amp; Limousine Commission (TLC) website](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page).

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.7 or higher
- Jupyter Notebook (optional, for running the provided notebook)
- Libraries: `pandas`, `matplotlib`, `seaborn`, `numpy`, `plotly`, `geopandas`, `folium`, `sklearn`

## Installation

Clone the repository and install the required Python libraries:

## Step-by-Step Analysis

### Step 1: Data Loading and Cleaning

1. Load the NYC Yellow Taxi dataset using `pandas`.
2. Clean the data by removing any missing values or outliers.
3. Convert relevant columns to appropriate data types (e.g., datetime).

---

### Step 2: Exploratory Data Analysis (EDA)

1. Generate summary statistics for numerical fields such as trip distance, fare amount, and passenger count.
2. Visualize the distribution of trip distances and fare amounts using **histograms**.

![Trip Distance Distribution](screenshots\trip_duration_distribution.png)    

---

### Step 3: Trip Duration Analysis

1. Calculate the **trip duration** as the difference between pickup and dropoff times.
2. Create a plot showing the distribution of trip durations.
3. Analyze trip durations based on different passenger counts.

_(Upload a screenshot of the Trip Duration Analysis here)_

![Trip Duration Analysis](path_to_screenshot_3.png)

---

### Step 4: Analyzing Fare Distribution

1. Plot a **scatter plot** to observe the relationship between trip distance and fare amount.
2. Use **box plots** to visualize fare distributions based on different passenger counts.

_(Upload a screenshot of the Fare Distribution here)_

![Fare Distribution](path_to_screenshot_4.png)

---

### Step 5: Visualizing Pickup and Dropoff Locations

1. Use **Folium** to create an interactive map for visualizing pickup locations.
2. Plot a heatmap to show the density of pickups across NYC.
3. Analyze patterns of pickups and drop-offs geographically.

_(Upload a screenshot of the Pickup Locations Heatmap here)_

![Pickup Locations Heatmap](path_to_screenshot_5.png)

---

### Step 6: Identifying Peak Hours and Days

1. Extract **hour** and **day** from the pickup time.
2. Create a **line plot** or **bar chart** to visualize the number of trips per hour and per day.
3. Identify the peak times for yellow taxi activity.

_(Upload a screenshot of the Peak Hours Analysis here)_

![Peak Hours Analysis](path_to_screenshot_6.png)

---

## Visualizations

Below are the visualizations created from the analysis:

- Data Cleaning Overview
- Trip Distance Distribution
- Trip Duration Analysis
- Fare Distribution Analysis
- Pickup Locations Heatmap
- Peak Hours & Days Analysis

---

## Project Structure

```bash
nyc-yellow-taxi-analysis/
│
├── data/
│   └── 2017_Yellow_Taxi_Trip_Data.csv  # Place the dataset here
│
├── notebook.ipynb
│
├── screenshots/
│   ├── trip_distance_distribution.png
│   ├── trip_duration_analysis.png
│   ├── fare_distribution.png
│   ├── pickup_locations_heatmap.png
│   └── peak_hours_analysis.png
│
├── README.md
└── LICENSE
```bash
git clone https://github.com/yourusername/nyc-yellow-taxi-analysis.git
cd nyc-yellow-taxi-analysis
pip install -r requirements.txt
```

## Contributing

If you would like to contribute to this project, feel free to fork the repository and submit a pull request. Contributions are welcome!

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- [NYC Taxi &amp; Limousine Commission (TLC)](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page) for providing the dataset.
- **Folium**, **Matplotlib**, and **Seaborn** for data visualization tools.
