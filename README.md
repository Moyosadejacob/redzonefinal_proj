# datahackerman_rdzone_proj

**Author**: Jacob Moyosade  
**Date**: 17th April 2025

This project is part of the Data Hackerman Red Zone initiative, focusing on analyzing parking data from the `park_birmingham_dataset`. The dataset contains parking occupancy data for various systems in Birmingham, including system code numbers, capacity, occupancy, and timestamps. The project performs data inspection, exploratory data analysis (EDA), and visualizations using Python libraries such as Pandas, Matplotlib, and Seaborn.

## Project Overview

The goal of this project is to analyze parking occupancy trends over time for the `BHMCCMKT01` system in the `park_birmingham_dataset`. The analysis includes:
- Data inspection to understand the dataset's structure and contents.
- Exploratory data analysis (EDA) to summarize key statistics.
- Visualizations to illustrate occupancy trends, occupancy percentage over time, and capacity vs. occupancy relationships.

## Features

- **Data Inspection**:
  - Loads the dataset (`dataset.csv`) using Pandas.
  - Converts the `LastUpdated` column to datetime format for time-series analysis.
  - Adds a `Time` column to extract time-only values (HH:MM:SS) for visualization.
  - Calculates the `Occupancy_Percentage` as a percentage of capacity.
- **Exploratory Data Analysis (EDA)**:
  - Summarizes the dataset with descriptive statistics (e.g., mean, min, max, standard deviation).
- **Visualizations**:
  - Bar chart: Occupancy over time (using the `Time` column).
  - Line plot: Occupancy percentage over time (using `LastUpdated`).
  - Line plots: Capacity and occupancy over time (using `LastUpdated`).
  - Bar chart: Capacity vs. occupancy.

## Project Structure

datahackerman_rdzone_proj/
│
├── data/
│   └── dataset.csv          # Dataset containing parking data
├── images/
│   ├── Occupancy percentage.png  # Line plot of occupancy percentage over time
│   ├── park_capacity plot.png    # Line plot of capacity over time
│   ├── park_occupancy plot.png   # Line plot of occupancy over time
│   └── park_birm_barchart.png    # Bar chart of capacity vs. occupancy
├── main.ipynb        # Jupyter Notebook with the project code
└── README.md                # Project documentation
## Prerequisites

- **Python 3.6 or higher**: Ensure Python is installed on your system. You can download it from [python.org](https://www.python.org/downloads/).
- **Required Libraries**:
  - `pandas`: For data manipulation and analysis.
  - `numpy`: For numerical operations.
  - `matplotlib`: For plotting visualizations.
  - `seaborn`: For enhanced visualizations.
- **Jupyter Notebook**: To run the provided script interactively.

## Installation

1. **Clone or Download the Repository**:
   - If using Git, clone the repository:

- Alternatively, download the ZIP file and extract it.

2. **Navigate to the Project Directory**:


3. **Set Up a Virtual Environment (highly Recommended)**:
- Create a virtual environment:

- Activate the virtual environment:
- On Windows:


4. **Install Required Libraries**:
- Install the necessary Python libraries:
pip install pandas numpy matplotlib seaborn jupyter notebook

## Usage

1. **Run Jupyter Notebook**:
- Start Jupyter Notebook from the project directory:

jupyter notebook

- This will open a browser window. Open the `main_script.ipynb` file.

2. **Execute the Notebook**:
- Run the cells in the notebook sequentially to:
- Load the dataset (`data/dataset.csv`).
- Perform data inspection and EDA.
- Generate visualizations.

3. **View the Visualizations**:
- The following plots are generated and saved in the `images/` directory:
- `Occupancy percentage.png`: Line plot showing occupancy percentage over time.
- `park_capacity plot.png`: Line plot showing capacity over time.
- `park_occupancy plot.png`: Line plot showing occupancy over time.
- `park_birm_barchart.png`: Bar chart showing capacity vs. occupancy.