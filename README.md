# Iris Data Analysis Project

**Author:** Manasa Alegala
**Course:** BDA400 - Data Science Tools and Techniques

## Overview
This project demonstrates a fundamental data science workflow in R using the built-in `iris` dataset. It includes data loading, exploratory data analysis (EDA), and basic visualizations to understand the relationships between different flower species based on their sepal and petal dimensions. 

## Project Structure
* `iris_analysis.R`: The main R script that performs data preparation, summary statistics, and plotting.
* `script_documentation.Rmd`: R Markdown documentation explaining the purpose, inputs, and outputs of the R script.

## Installation & Dependencies
To run this project locally, you will need R installed on your system. The script uses the following packages:
* `ggplot2` (for data visualization)
* `dplyr` (for data manipulation)

You can install these dependencies in R using:
```R
install.packages(c("ggplot2", "dplyr"))

Example Usage
To reproduce the analysis, run the main script in your R environment:
source("iris_analysis.R")
This will print a summary of the dataset to the console and generate a scatter plot displaying Sepal Length vs. Sepal Width.

License
This project is licensed under the MIT License. You are free to use, modify, and distribute this code for educational purposes.

AI Assistance Disclosure
AI Tool Used: ChatGPT (Free tier).

Main Prompts: "Generate a professional README for an R data analysis project using the Iris dataset," and "Add sections for Installation, Example Code, and License."

Changes Made: I formatted the code blocks manually to ensure they render correctly in GitHub Markdown, and added the specific package installation instructions (install.packages) after reviewing the AI's output.