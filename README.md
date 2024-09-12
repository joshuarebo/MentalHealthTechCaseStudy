# Mental Health in Technology-related Jobs Case Study

## Overview
This repository contains the code and resources for the case study titled **"Mental Health in Technology-related Jobs."** The analysis aims to explore the impact of mental health on employees in the tech industry using clustering techniques.

## Project Structure
The project directory is organized as follows:
- **`data/`** - Contains the dataset used for analysis.
- **`DataExploration.ipynb/`** - Contains Python scripts for data preprocessing, clustering, and visualization.
- **`results/`** - Contains generated plots and tables.
- **`README.md`** - This file, providing an overview and instructions.

## Dataset
The dataset used is **`mental-heath-in-tech-2016_20161114.csv`** and is located in the `data/` folder as obtained from https://www.kaggle.com/osmi/mental-health-in-tech-2016. It contains various attributes related to job stress, satisfaction, and work-life balance.

## Installation
To run the analysis, make sure you have Python 3.12.4 installed. You will also need several Python packages. You can install these packages using a `requirements.txt` file if available.

### Installing Packages
If a `requirements.txt` file is included, you can install the required packages using:
```bash
pip install -r requirements.txt
If you do not have a requirements.txt file, you may manually install the necessary packages:

bash
Copy code
pip install pandas matplotlib seaborn missingno scikit-learn
Running the Code
Load the Dataset The dataset file is located in the data/ folder.

Run the DataExploration.ipynb Scripts Navigate to the scripts/ folder in your terminal and execute the following Python scripts in order:

Data Preparation and Visualization Reduction and Clustering Analysis all organized in one Notebook

bash
Copy code
python DataExploration.ipynb
Dimensionality Reduction and Clustering Analysis

bash
Copy code
python DataExploration.ipynb
The scripts will perform data preprocessing, clustering, and generate visualizations.

View Results Check the results/ folder for the output of the analysis, including:

PCA Scatter Plot: Visual representation of clusters in a 2D space based on PCA.
t-SNE Scatter Plot: Detailed view of cluster distribution.
Cluster Summary Table: Contains average stress levels, job satisfaction, and work-life balance for each cluster.

Example Visualizations
The following images can be found in the results/ folder:
PCA Scatter Plot
t-SNE Scatter Plot
Cluster Summary Statistics Table
Contributing

If you have suggestions or improvements, feel free to fork the repository and submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
Joshua Rebo
Email: [joshuarebo04@gmail.com]
GitHubprofile: joshuarebo