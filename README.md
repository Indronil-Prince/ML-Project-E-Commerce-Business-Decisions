**Read Here:** [Project Report](https://github.com/Indronil-Prince/ML-Project-E-Commerce-Business-Decisions/blob/main/Phase%205/Stage5_Report_Gamma.pdf)

# Stage5.py Analysis Script

This Python script (`stage5.py`) is designed to analyze data using machine learning techniques and visualize the results effectively. The script uses a variety of data science and machine learning libraries to process data and generate insightful plots.

## Requirements

The script requires the following Python packages:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn` (scikit-learn)
- `treeinterpreter` (installable via pip)

To install these packages, you can run:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn treeinterpreter
```

## How to Run

1. **Ensure All Required Packages Are Installed:** Make sure all dependencies are installed using the command above.

2. **Execute the Script:** Run the `stage5.py` file in your Python environment with:
   ```bash
   python stage5.py
   ```

   The script will generate relevant outputs, metrics, and visualizations based on the provided datasets.

## Code Organization

- **Import Statements:** Imports necessary data science, visualization, and machine learning libraries.
- **Dataset Loading:** Loads datasets from scikit-learn or other sources.
- **Data Analysis & Processing:** Performs exploratory data analysis, preprocessing, and feature engineering.
- **Model Building:** Implements machine learning models and interprets results using the `treeinterpreter` package.
- **Visualization:** Plots relevant visualizations to represent results.

## Dataset Information

This script uses existing datasets available through scikit-learn. Make sure to explore and customize data handling to meet your specific needs. If using other datasets, replace the loading methods with appropriate file paths or URLs. Ensure that csv files are locally placed with the script or update the file paths to wherever they are located.

**Links to datasets**
* Online Shoppers Purchasing Intention Data Set
	https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset
* Sales of Summer Clothes in E-commerce Wish
	https://www.kaggle.com/datasets/jmmvutu/summer-products-and-sales-in-ecommerce-wish/data?select=summer-products-with-rating-and-performance_2020-08.csv
	https://www.kaggle.com/datasets/jmmvutu/summer-products-and-sales-in-ecommerce-wish/data?select=computed_insight_success_of_active_sellers.csv
