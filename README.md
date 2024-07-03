# Student-Performance-Analysis-Data-Cleaning-Project
Data cleaning project using student-mat.csv from UCI ML Repository. Analyzing student performance in secondary education, focusing on Mathematics. Includes grades, demographics, and social factors. Preparing data for analysis, showcasing best practices in data cleaning and preparation.



# Student Performance Analysis: Data Cleaning Project

## Overview
This repository contains a data cleaning project focused on analyzing student performance in secondary education, specifically in Mathematics. The project utilizes the `student-mat.csv` dataset from the UCI Machine Learning Repository, which includes student grades, demographic, social, and school-related features collected via school reports and questionnaires.

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
git clone https://github.com/escobar192011/student-performance-analysis.git


2. Navigate into the project directory:
cd student-performance-analysis



3. Install the required dependencies:
pip install pandas numpy matplotlib # Add any other dependencies

## Usage
### Running Jupyter Notebooks

1. Ensure you have Jupyter Notebook installed. If not, install it using:
pip install jupyter

2. Clone the repository and navigate into the project directory:
git clone https://github.com/escobar192011/student-performance-analysis.git
cd student-performance-analysis

3. Start Jupyter Notebook:
jupyter notebook

4. Open the notebook `student_performance_uci_mlr_data_cleaning.ipynb`

### Executing Code

- Run all cells in the notebook to execute the data cleaning and analysis processes.
- Modify parameters or experiment with different approaches as needed.

### Interpreting Results

- The notebook will output visualizations and summaries that analyze student performance based on the `student-mat.csv` dataset.

### Additional Dependencies

- Ensure you have Python 3.x installed along with the libraries specified in the installation section (`pandas`, `numpy`, `matplotlib`, etc.).

### Example Usage

- Explore different data cleaning techniques or modify visualizations to gain insights into student performance factors.
- Experiment with machine learning models or statistical analyses if extending the project's scope.

## Data Description
The `student-mat.csv` dataset contains 395 entries and includes the following columns:
- `school`: student's school (binary: 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira)
- `sex`: student's sex (binary: 'F' - female or 'M' - male)
- `age`: student's age (numeric: from 15 to 22)
- `address`: student's home address type (binary: 'U' - urban or 'R' - rural)
- ...

For a detailed description of each column, refer to the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Student+Performance).

## File Structure
The project directory is organized as follows:

- **`README.md`**: This file provides an overview of the project, installation instructions, usage guidelines, and other relevant information.

- **`data/`**: Directory containing datasets used in the project.
  - `student-mat.csv`: Dataset from the UCI Machine Learning Repository, containing student performance data in Mathematics.

- **`notebooks/`**: Directory containing Jupyter Notebooks for data analysis and visualization.
  - `student_performance_uci_mlr_data_cleaning.ipynb`: Notebook for data cleaning tasks, preprocessing `student-mat.csv`.
  - `student_performance_uci_mlr_exploratory_analysis.ipynb`: Notebook for exploring and visualizing student performance metrics.
 
-- **`scripts/`**: Directory for Python scripts used in the project.
  - `__init__.py`: Makes the directory a package.
  - `data_preprocessing.py`: Script for preprocessing data before analysis.
  - `visualization_utils.py`: Script containing utility functions for data visualization. 

- **`LICENSE`**: File specifying the terms under which the project code can be used, modified, and distributed (typically under the MIT License).

- **`requirements.txt`**: File listing Python dependencies required to run the project (`pandas`, `numpy`, `matplotlib`, etc.).

- **`.gitignore`**: File specifying which files and directories to ignore in version control (e.g., virtual environment folders, sensitive information).

Ensure you have the necessary datasets (`data/student-mat.csv`) and dependencies installed as outlined in the `README.md` before running the notebooks or scripts.

## Contributing
If you'd like to contribute to this project, follow these steps:
- Fork the repository on GitHub
- Clone your forked repository
- Create a new branch for your feature or bug fix
- Make your changes and submit a pull request

## License
This project is licensed under the [MIT License](LICENSE).
