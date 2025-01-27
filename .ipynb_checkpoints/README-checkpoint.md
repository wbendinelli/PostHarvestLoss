
# Post-Harvest Loss Analysis

![Project Overview](https://via.placeholder.com/800x300?text=Post-Harvest+Loss+Analysis)

## Project Overview

This project investigates the primary factors contributing to post-harvest grain losses. By analyzing various datasets and employing econometric models, we aim to identify key determinants and propose strategies to mitigate these losses.

## Objectives

- Identify the main factors influencing post-harvest grain losses.
- Quantify the impact of each factor using econometric modeling.
- Compare findings with existing literature to highlight novel insights.

## Novel Contributions

![Data Analysis](https://via.placeholder.com/800x300?text=Data+Analysis)

While previous studies have explored post-harvest losses, this project differentiates itself by:

- Utilizing a comprehensive dataset that integrates multiple variables not previously analyzed collectively.
- Applying advanced econometric techniques to control for potential confounders.
- Providing actionable recommendations based on robust statistical evidence.

## Project Structure

The repository is organized as follows:

```
PostHarvestLoss/
├── data/
│   ├── raw/        # Unprocessed datasets
│   ├── processed/  # Cleaned and transformed data
├── notebooks/      # Jupyter notebooks for exploration and analysis
├── src/            # Source code for data processing and analysis
│   ├── data/       # Data handling and preprocessing scripts
│   ├── models/     # Scripts for modeling and evaluation
├── tests/          # Unit tests for your code
├── reports/        # Generated analysis reports and visualizations
├── config/         # Configuration files
└── README.md       # Project overview and instructions
```

## Installation and Setup

![Installation](https://via.placeholder.com/800x300?text=Installation+Steps)

### Clone the repository
```bash
git clone https://github.com/wbendinelli/PostHarvestLoss.git
cd PostHarvestLoss
```

### Create and activate a virtual environment
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

### Install the required packages
```bash
pip install -r requirements.txt
```

## Usage

### Data Processing
Execute the ETL process by running:
```bash
python src/data/etl_phl.py
```

### Analysis
Open and run the Jupyter notebooks in the `notebooks/` directory to perform exploratory data analysis and modeling.

## Data Sources

The datasets used in this project are sourced from the Food and Agriculture Organization (FAO) and are widely documented in the literature:

- **Food Balance Sheets**: `FoodBalanceSheetsHistoric_E_All_Data_(Normalized).csv`
- **Food Security Indicators**: `Food_Security_Data_E_All_Data_(Normalized).csv`
- **Trade Indices**: `Trade_Indices_E_All_Data_(Normalized).csv`
- **Price Data**: `Prices_E_All_Data_(Normalized).csv`

*Ensure to review and comply with the data usage policies of each source.*

## Results

![Results](https://via.placeholder.com/800x300?text=Results)

Our analysis revealed that factors such as infrastructure, economic development, and trade openness significantly influence post-harvest grain losses. These findings suggest that interventions targeting these areas could effectively reduce losses. Detailed results and visualizations are available in the `reports/` directory.

## Contributing

We welcome contributions to enhance this project. Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`
3. Make your changes and commit them: `git commit -m 'Description of feature'`
4. Push to the branch: `git push origin feature-branch-name`
5. Submit a pull request detailing your changes.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

We extend our gratitude to the Food and Agriculture Organization (FAO) for providing the datasets and to colleagues for their invaluable insights during this research.
