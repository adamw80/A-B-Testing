# A/B Testing and Statistical Analysis

## Overview
This project evaluates the effectiveness of product changes through A/B testing and statistical analysis. By testing differences in user behavior between two product versions, the project aims to determine whether changes result in significant improvements in performance metrics such as conversion rates.

## Dataset
The dataset contains user interaction data with the following key variables:
- **Group:** Indicates whether the user was part of the control or test group.
- **Conversion:** Binary indicator of whether a conversion event occurred (0 or 1).
- **Other Metrics:** Additional metrics depending on the test setup, such as time spent or number of clicks.

## Key Objectives
1. Perform A/B testing on conversion rates and other relevant metrics.
2. Apply statistical tests, including Pearson’s chi-square test, to measure significance.
3. Provide actionable recommendations based on test outcomes.

## Project Structure
```
.
├── README.md                 # Documentation file
├── A-B_Testing.ipynb         # Main analysis notebook
├── data/                     # Input datasets
├── results/                  # Outputs such as statistical test results and plots
└── reports/                  # Summaries and recommendations
```

## Key Features
- **A/B Testing Setup:** Defines test and control groups, calculates conversion rates, and prepares data.
- **Statistical Analysis:** Uses Pearson’s chi-square test and other statistical tests to evaluate significance.
- **Recommendations:** Provides recommendations based on test outcomes and statistical evidence.

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ab-testing.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Open and execute the `A-B_Testing.ipynb` notebook in a Jupyter environment to follow the analysis and view results.

## Results
- Comparison of performance metrics between control and test groups.
- Statistical significance of observed differences.
- Actionable recommendations based on findings.

## License
This project is licensed under the MIT License.

## Contact
For questions or feedback, feel free to reach out:
- **Email:** Adam.RivardWalter@gmail.com  
- **GitHub:** [adamw80](https://github.com/adamw80)
