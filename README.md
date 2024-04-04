# Portuguese Schools Math Results Analysis

## Overview

This repository contains Python scripts for analyzing math results data from two Portuguese schools. The analysis includes normalization of the data and subsequent analysis with recommendations based on the findings.

## Contents

- **data**: Directory containing the data files for the analysis.
- **normalize_data.py**: Python script for data normalization.
- **analyze_results.py**: Python script for data analysis and recommendations.
- **README.md**: This file providing an overview of the project.

## Data

The data files are stored in the `data` directory. Each file contains math results and various variables for students in the respective schools.

## Normalization

The `normalize_data.py` script performs data normalization to ensure consistency and comparability across different variables. Normalization techniques may include scaling, standardization, or other methods to transform the data into a common scale.

## Analysis and Recommendations

The `analyze_results.py` script conducts an in-depth analysis of the normalized data and provides recommendations based on the findings. The analysis may include:

- Exploratory data analysis (EDA) to uncover patterns and trends.
- Statistical analysis to identify correlations and relationships between variables.
- Machine learning techniques for predictive modeling or clustering.
- Recommendations for improving student performance or addressing areas of concern.

## Usage

1. Ensure Python is installed on your system.
2. Place the data files in the `data` directory.
3. Run the `normalize_data.py` script to perform data normalization.
4. Run the `analyze_results.py` script to conduct the analysis and view recommendations.

```bash
python normalize_data.py
python analyze_results.py
