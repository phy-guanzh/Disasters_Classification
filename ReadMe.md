# Disaster Classification Analysis

This repository contains datasets and analysis scripts for exploring disasters across Africa and South America. It covers data cleaning, visualization, feature engineering, dimensionality reduction (PCA), and classification.

---

## Folder Structure

### Data Folders
- **`original_data/`**  
  Contains the originally downloaded datasets, divided into:  
  - `Africa/`  
  - `South_America/`

- **`cleaned_data/`**  
  Contains datasets after **Data Cleaning** and **Feature Engineering**.

- **`pca_data/`**  
  Contains datasets including PCA results and the datasets used for classification.

---

## Script Descriptions

### 1. `Africa_combined.Rmd`  
This script includes:  
- **Data Cleaning**  
- **Data Visualization**  
- **PCA Analysis**  
- **Regression Analysis**:  
  - Using the **originally cleaned dataset**.  
  - Using the **PCA-transformed dataset**.  
Applied to **African countries**.

---

### 2. `South_America_combined.Rmd`  
This script includes:  
- **Data Cleaning**  
- **Data Visualization**  
- **PCA Analysis**  
- **Regression Analysis**:  
  - Using the **originally cleaned dataset**.  
  - Using the **PCA-transformed dataset**.  
Applied to **South American countries**.

---

### 3. `Classification_binary.Rmd`  
This script performs **binary classification** to predict the **CONTINENT** where a disaster occurred (Africa or South America).

---

### 4. `Classification_multi.Rmd`  
This script performs **multi-class classification** to predict the **DISASTER CATEGORY**, which includes 17 different types of disasters.

---

## How to Run

### Prerequisites

1. Install **R** (version 2024.04.2+764 or later).  
2. Install **RStudio** (recommended for running `.Rmd` files).  



