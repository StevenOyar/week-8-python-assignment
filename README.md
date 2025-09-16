# week-8-python-# CORD-19 

## Overview
This project provides a comprehensive analysis of the CORD-19 dataset, focusing on COVID-19 research publications. The analysis includes data cleaning, exploratory data analysis, visualization, and an interactive Streamlit web application.

## ⚠️ Data Download Required

**The dataset files are NOT included in this repository due to their large size (300+ MB).**

### Download Instructions
1. **Visit Kaggle**: https://www.kaggle.com/datasets/allen-institute-for-ai/CORD-19-research-challenge?select=metadata.csv
2. **Download** the `metadata.csv` file
3. **Place** the file in the same directory as your Python scripts

## Features

### 📊 Data Analysis
- **Data Cleaning**: Comprehensive missing value handling
- **Time Series Analysis**: Publication trends over time
- **Journal Analysis**: Top publishing journals
- **Text Analysis**: Most frequent words in titles and word clouds
- **Source Distribution**: Papers by data source

### 🖥️ Interactive Streamlit App
- **Real-time filtering**: Year range selection
- **Dynamic visualizations**: Interactive charts and plots
- **Data exploration**: Sample data viewing
- **User-friendly interface**: Simple navigation

## Installation and Setup

### 1. Download the Data
```bash
# Visit the Kaggle link above and download metadata.csv
# Place it in your project directory
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Analysis
```bash

# run the interactive Streamlit app
streamlit run app1.py
```

## Key Findings
- **Publication Growth**: Significant increase in COVID-19 research during 2020-2021
- **Top Journals**: Identified leading journals in COVID-19 research
- **Research Focus**: Common terms indicate focus on clinical studies and epidemiology
- **Data Quality**: Successfully handled missing values in multiple columns

## Technologies Used
- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **Matplotlib/Seaborn**: Data visualization
- **Streamlit**: Interactive web application
- **WordCloud**: Text visualization
- **Plotly**: Interactive charts (in advanced version)

## Troubleshooting

### Common Issues
- **"FileNotFoundError"**: Download metadata.csv from the Kaggle link above
- **Memory Issues**: The dataset is large - ensure sufficient RAM (4GB+ recommended)
- **Slow Loading**: First run may be slow due to data processing

### Data Sources
- **Primary source**: [CORD-19 on Kaggle](https://www.kaggle.com/datasets/allen-institute-for-ai/CORD-19-research-challenge)


## Contributing
Feel free to fork this repository and submit pull requests for improvements.

## License
This project is for educational purposes. Please respect the CORD-19 dataset license terms.

## Acknowledgments
- **Kaggle** for hosting the dataset
- **Streamlit** for the excellent web app framework
