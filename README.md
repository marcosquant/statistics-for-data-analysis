# Statistics for Data Analysis - Udacity

Repository with projects developed during the **[Statistics for Data Analysis Nanodegree](https://www.udacity.com/course/statistics-for-data-analysis-nanodegree--nd588)** by Udacity.

## Projects

| # | Project | Description | Techniques |
|---|---------|-------------|------------|
| 3 | [Analyze A/B Test Results](project_3/) | Statistical analysis of an A/B test for an e-commerce website to evaluate whether a new page design should be implemented | Descriptive Statistics, Probability, Hypothesis Testing, A/B Testing |

## Project 3 - Analyze A/B Test Results

This project investigates the results of an A/B test run by an e-commerce website. The goal is to analyze conversion behavior across control and treatment groups and support a decision about whether the company should implement a new page design, keep the existing page, or continue the experiment for longer.

The analysis includes:

- Descriptive statistics of visitors and conversion rates
- Probability-based comparisons between groups
- A/B test interpretation
- Statistical reasoning for product decision-making

## Repository Structure

```text
.
|-- project_3/
|   |-- analyze_ab_test_results_project.ipynb
|   |-- analyze-a_b-test-results-template.pptx
|   `-- data/
|       `-- ab_data.csv
|-- .gitignore
`-- README.md
```

## Technologies

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/marcosquant/statistics-for-data-analysis.git
   cd statistics-for-data-analysis
   ```

2. Install the dependencies:

   ```bash
   pip install numpy pandas matplotlib jupyter
   ```

3. Navigate to the project folder and open the notebook:

   ```bash
   cd project_3
   jupyter notebook analyze_ab_test_results_project.ipynb
   ```

## Author

**Marcos Roberto Souza** - [Statistics for Data Analysis Nanodegree](https://www.udacity.com/course/statistics-for-data-analysis-nanodegree--nd588), Udacity.
