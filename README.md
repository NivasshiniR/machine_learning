# Waste Classification with Logistic Regression and Random Forest

This project focuses on classifying different types of waste images using machine learning algorithms, specifically Logistic Regression and Random Forest classifiers. The dataset consists of images annotated with their bounding box coordinates and corresponding labels.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview
The goal of this project is to train machine learning models to classify waste images into various categories such as "Bottle," "Carton," "Can," etc. The project involves the following steps:
- Data preprocessing
- Feature selection
- Training and evaluating models (Logistic Regression and Random Forest)

## Dataset
The dataset used in this project contains images with their bounding box coordinates and class labels. Below is a sample of the dataset structure:

| filename          | width | height | class      | xmin | ymin | xmax | ymax |
|-------------------|-------|--------|------------|------|------|------|------|
| batch_1_000006.jpg | 1537  | 2049   | Bottle     | 517  | 127  | 964  | 1449 |
| batch_1_000008.jpg | 1537  | 2049   | Carton     | 1    | 457  | 1430 | 1976 |
| ...               | ...   | ...    | ...        | ...  | ...  | ...  | ...  |

## Installation
To run this project, you'll need to have Python installed along with the necessary packages. You can install the required packages using `pip`:

```bash
pip install -r requirements.txt
