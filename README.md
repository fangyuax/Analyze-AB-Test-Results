# Analyze-AB-Test-Results
Data analysts and data scientists frequently conduct A/B tests. This project is to analyze the outcomes of an A/B test carried out by an e-commerce site. The objective is to use this notebook to assist the company in determining whether to adopt the new page, retain the old page, or extend the experiment duration to make a decision.

This repository contains a Jupyter Notebook file, which is used to perform data analysis and data visualization. The notebook is designed to work with a specific dataset or problem statement, and can be used to explore and analyze the data in an interactive manner.

## Summary of Findings
Based on the p-vlaue, we could see there is not statistical signifiance value of the countries, which mean the patient in different countries who get a new page would not change to the conversion rate. Moreover, the p-values that are calculated at Part II and Part III show that we should accept our null hypothesis, which is the new pages and old pages do not have significant differences in this study.

## Installation
To use this notebook file, you will need to have Jupyter Notebook installed on your computer. Once you have installed Jupyter Notebook, you can download or clone this repository to your local machine.

## Usage

To open and run the notebook file, navigate to the directory where you have saved the file and run the command jupyter notebook in your terminal or command prompt. This will launch Jupyter Notebook in your default browser, where you can select the notebook file and start working on it.

The notebook file contains cells with Python code, as well as markdown cells with text and instructions. You can execute each code cell by clicking on it and pressing Shift + Enter. You can also edit the code and text cells as needed to perform your analysis.

## Dependencies

This notebook file requires certain Python packages to be installed, such as pandas, numpy, and matplotlib. You can install these packages by running the command pip install <package-name> in your terminal or command prompt.

 ```bash
import pandas as pd
import numpy as np
import random
import matplotlib.pyplot as plt
```

## Contributing
If you find any issues with this notebook file, or if you have any suggestions for improvement, please feel free to open an issue or submit a pull request.
