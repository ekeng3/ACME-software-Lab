
# Road Traffic Accidents EDA (2020)

## Project Overview

This project conducts an Exploratory Data Analysis (EDA) on road traffic accident data from 2020. The analysis aims to uncover patterns, trends, and insights that could potentially inform road safety policies and decision-making processes.

## Table of Contents

1. [Installation](#installation)
2. [Project Structure](#project-structure)
3. [Usage](#usage)
4. [Data Source](#data-source)
5. [Key Insights](#key-insights)
6. [Future Work](#future-work)
7. [Contributing](#contributing)
8. [License](#license)

## Installation

To run this project, you need to have Python installed on your system. The project uses several Python libraries for data analysis and visualization. You can install these dependencies using the following command:

```
pip install pandas numpy matplotlib seaborn
```

## Project Structure

The main component of this project is a Jupyter notebook:

- `EDA_on_Road_Traffic_Accidents.ipynb`: The main notebook containing the entire analysis process.

## Usage

To use this project:

1. Clone the repository to your local machine.
2. Ensure you have the required dependencies installed (see [Installation](#installation)).
3. Open the `EDA_on_Road_Traffic_Accidents.ipynb` notebook in Jupyter Lab or Jupyter Notebook.
4. Run the cells in order to reproduce the analysis.

## Data Source

The dataset used in this analysis is a CSV file containing road accident data for the year 2020. The main data source is in a SQLite database
accident_data_v1.0.0_2023.db. Download the dataset at https://rb.gy/r19j12 (The EDA_data_source_&_extraction notebook contains the codes showing how the csv was extracted from the database)

## Key Insights

The EDA process revealed several important insights about road accidents in 2020:

1. There are missing values in the 'latitude' and 'longitude' columns, which may affect geographical analysis.
2. Several columns have more unique values than expected, suggesting potential data quality issues or the need for category consolidation.
3. The analysis explores various factors such as accident severity, road type, weather conditions, and time of occurrence.

For more detailed insights, please refer to the Jupyter Notebook.

## Future Work

Based on the initial analysis, several areas for future work have been identified:

1. Address data quality issues, particularly in categorical variables with unexpected values.
2. Develop predictive models for accident severity or frequency.
3. Consider integrating additional datasets to provide more context.

## Contributing

Contributions to this project are welcome. Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).
