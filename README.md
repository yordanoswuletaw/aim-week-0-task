# Task 1: Git and GitHub | Project Planning - EDA & Stats

This repository contains the deliverables for **Task 1** focused on Git and GitHub usage, setting up a Python environment, and performing exploratory data analysis (EDA) with statistical insights.

## Objectives

### **Git and GitHub**
- Set up the development environment for Python.
- Use Git for version control and GitHub for collaboration.
- Implement CI/CD pipelines.

### **EDA & Statistics**
- Gain an understanding of the dataset.
- Perform Exploratory Data Analysis to uncover insights and patterns.
- Demonstrate statistical thinking through plots and distributions.

---

## Key Performance Indicators (KPIs)
- **Dev Environment Setup**: Ensure Python environment and GitHub repository are correctly configured.
- **Relevant Skills Demonstrated**: Show proficiency in using Git, GitHub, and EDA techniques.
- **EDA Outputs**: Provide actionable insights supported by statistical evidence.

---

## Tasks Overview

### **Git and GitHub**
1. Create a GitHub repository for this task.
2. Add a branch named `task-1` to track your day-one analysis.
3. Commit changes at least three times daily with descriptive commit messages.
4. Configure CI/CD pipeline using GitHub Actions.

### **EDA & Statistical Analysis**
Perform the following analyses on the dataset:

1. **Summary Statistics**
   - Calculate metrics like mean, median, and standard deviation for numeric columns.

2. **Data Quality Check**
   - Identify missing values, outliers, and incorrect entries in critical columns.

3. **Time Series Analysis**
   - Analyze and visualize trends in `GHI`, `DNI`, `DHI`, and `Tamb` over time.

4. **Correlation Analysis**
   - Study relationships among solar radiation components, temperature, and wind conditions.

5. **Wind Analysis**
   - Visualize wind speed and direction trends using wind roses or radial bar plots.

6. **Temperature Analysis**
   - Examine the relationship between relative humidity (`RH`) and solar radiation or temperature.

7. **Histograms**
   - Create histograms for key variables like `GHI`, `DNI`, and temperature.

8. **Z-Score Analysis**
   - Detect outliers by calculating Z-scores for numeric columns.

9. **Bubble Charts**
   - Use bubble charts to explore complex relationships among variables.

10. **Data Cleaning**
    - Handle missing values, anomalies, and null columns (`Comments`).

---

## Repository Structure

```plaintext
├── .vscode/
│   └── settings.json            # VS Code settings for environment setup
├── .github/
│   └── workflows/
│       ├── unittests.yml        # CI/CD pipeline for unit tests
├── .gitignore                   # Ignored files and folders
├── requirements.txt             # Dependencies for the project
├── README.md                    # Documentation of the repository
├── src/                         # Source code for analysis and processing
├── notebooks/
│   ├── __init__.py              # Package initialization
│   └── README.md                # Documentation for the notebooks
├── tests/
│   ├── __init__.py              # Test initialization
└── scripts/
    ├── __init__.py              # Scripts package initialization
    └── README.md                # Documentation for scripts
```

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yordanoswuletaw/aim-week-0-task.git
   cd aim-week-0-task
   ```

2. Create a virtual environment:
   ```bash
   python3 -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Use the `task-1` branch for this task:
   ```bash
   git checkout task-1
   ```

2. Follow the tasks outlined in this README to perform EDA and statistical analysis.

3. Commit your progress regularly with descriptive messages:
   ```bash
   git add .
   git commit -m "Descriptive commit message"
   git push origin task-1
   ```

---

## Contribution Guidelines

1. Use feature branches for new tasks.
2. Follow the folder structure and naming conventions.
3. Provide clear and descriptive commit messages.

---

## Results and Insights

All findings from the EDA and statistical analysis will be documented in the **notebooks/README.md** and supported by visualizations.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

--- 

This README ensures your repository is well-documented and provides clear instructions for contributors and reviewers.