# task-1-iris-data-visualization
Exploring and visualizing the Iris dataset using Python.
# Task 1: Iris Dataset Exploration & Visualization

## Objective
Explore and visualize the Iris dataset to understand data distributions, relationships, and outliers.

## Dataset
- Iris Dataset
- Source: Seaborn / UCI Machine Learning Repository

## Steps Performed
- Loaded dataset using pandas
- Inspected shape, columns, and first rows
- Used info() and describe() for statistics
- Created:
  - Scatter plots
  - Histograms
  - Box plots

## Visualizations
- Feature relationships using scatter plots
- Distribution analysis using histograms
- Outlier detection using box plots

## Tools & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn

## Outcome
Basic understanding of data trends and feature relationships.
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
# Load iris dataset from seaborn
df = sns.load_dataset('iris')
