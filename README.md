# Mushroom Classification: Edible vs Poisonous

This project builds a machine learning model to classify mushrooms as edible or poisonous using their physical characteristics. The repository contains the dataset, project notebook, and guide used for the ML-I Lab project.

## Project Guide

This project was completed under the guidance of
**Dr. Anjum Y. Mansuri**, Assistant Professor, Computer Applications,
LJ Institute of Computer Applications, LJ University, Ahmedabad.

GitHub: [@anjum-mansuri](https://github.com/anjum-mansuri)

Course: ML-I Lab (IMCA Sem V) | Project ID: P07

## Overview

The goal is to classify mushrooms into two classes:

- `e` = Edible
- `p` = Poisonous

The model considers 22 categorical features such as:

- cap shape and color
- cap surface
- bruises
- odor
- gill size and color
- stalk shape, root, and color
- ring type and number
- spore print color
- population and habitat

## Dataset

- Source: UCI Machine Learning / Kaggle Mushroom Classification dataset
- Link: https://www.kaggle.com/datasets/uciml/mushroom-classification
- Format: CSV
- Rows: 8,124
- Columns: 23 total (22 features + target column)

## Repository Structure

- `D51_P46_starter.ipynb` — main Jupyter notebook containing the training workflow
- `mushrooms.csv` — mushroom dataset used for classification
- `P46_Project_Guide.html` — project guide with step-by-step instructions
- `README.md` — project overview and usage guide

## Objective

Build a machine learning model that can predict mushroom toxicity with strong performance while paying special attention to the poisonous class, since missing a poisonous mushroom is more dangerous than a false positive.

## Model Used

- Algorithm: Decision Tree Classifier
- Task: Binary classification
- Main evaluation metric: Recall for the poisonous class

## Tools and Libraries

This project uses Python libraries such as:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Installation

Install the required dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
