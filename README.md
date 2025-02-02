# UK GDHI Analysis

## Project Overview

This project analyzes Gross Disposable Household Income (GDHI) data for selected UK cities: London, York, Belfast, and Edinburgh. The analysis includes national GDHI trends, city comparisons, and year-on-year growth rates.

## Features

- **Data Filtering & Cleaning**: Extracts relevant GDHI data from a large dataset.

- **National vs. City Comparison**: Calculates national GDHI averages and compares them with selected cities.

- **Visualization**: Generates multiple graphs for GDHI trends and year-on-year growth rates.

- **Kepler.gl Data Export**: Prepares geographic data for visualization in Kepler.gl.

## Installation & Usage

## Input Dataset

The input dataset is available at: [ONS GDHI Dataset](https://www.ons.gov.uk/file?uri=/economy/regionalaccounts/grossdisposablehouseholdincome/datasets/regionalgrossdisposablehouseholdincome/1997to2021/regionalgrossdisposablehouseholdincomeallitlregions2021.xlsx)

1. **Clone the Repository**
  ```bash
  git clone https://github.com/your-username/gdhi-analysis.git
  cd gdhi-analysis
   ```

2. **Set Up Dependencies**

  Make sure you have Python installed, then install the required packages:
  ```bash
  pip install -r requirements.txt
   ```

3. **Run the Analysis**

  Execute the Jupyter Notebook to generate visualizations and analyze GDHI data:
  ```bash
  jupyter notebook gdhi_analysis.ipynb
   ```

4. **Export Data for Kepler.gl**

  To generate a CSV file for geographic visualization, run:
  ```bash
  python export_kepler_data.py
   ```

This will create gdhi_kepler_2021.csv, which can be uploaded to Kepler.gl for interactive mapping.

## Example Visualizations

The project generates multiple graphs, such as:

- GDHI Growth Comparison for Selected Cities

- Year-on-Year GDHI Growth Rate

- National vs. City-Level GDHI Trends

All plots are saved in the output_graphs/ directory.

## Contact
For any questions or feedback, reach out to:
- **Email**: [jakubtrnka16@gmail.com](mailto:jakubtrnka16@gmail.com)
- **GitHub**: [https://github.com/jtrnka16](https://github.com/jtrnka16)
