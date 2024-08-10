# Health Monitoring and Analysis

## Overview

The **Health Monitoring and Analysis** project involves analyzing health-related data to gain insights into various health metrics. The dataset includes information on age, gender, heart rate, blood pressure, respiratory rate, body temperature, oxygen saturation, activity level, sleep quality, and stress level. The goal is to explore and visualize these metrics to identify patterns and correlations that could be useful in health monitoring.

## Features

- **Handling Missing Data**: Missing values in `BodyTemperature` and `OxygenSaturation` are filled using the median to maintain data integrity.
- **Statistical Analysis**: Summary statistics provide a quick overview of the central tendencies, dispersion, and shape of the data distribution.
- **Visualizations**: 
  - Distribution plots for numerical health metrics.
  - Gender distribution co-releation chart.
  - Correlation heatmap to identify relationships between health metrics.
  - Boxplots to analyze heart rate and oxygen saturation by gender, sleep quality, stress level, and activity level.
  - Blood pressure distribution histograms.
- **Categorization**: Age groups, blood pressure categories, heart rate categories, and oxygen saturation levels are categorized for deeper analysis.

## Installation

To run this project on your local machine, follow these steps:

### Prerequisites

- Python 3.x
- `pandas`
- `matplotlib`
- `seaborn`

### Clone the Repository

```bash
git clone https://github.com/KishoreRaghupathy/Health-Monitoring-and-Analysis.git
cd health-monitoring-analysis
```

### Install Required Libraries

If you don't have the required Python packages, you can install them using:

```bash
pip install -r requirements.txt
```

### Run the Analysis

You can run the analysis by executing the provided Python script or Jupyter notebook:

```bash
python health_analysis.py
```

or

```bash
jupyter notebook health_analysis.ipynb
```

## Usage

Once the project is set up, you can explore the health metrics and visualize the data to draw conclusions that could assist in health monitoring and decision-making.

## Contributing

If you would like to contribute to this project, please feel free to submit a pull request. All contributions are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
