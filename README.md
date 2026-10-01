# DVC Assignment

## Objective

This project demonstrates dataset version control using Git and DVC.

## Tools Used

- Python
- Pandas
- Scikit-learn
- Git
- GitHub
- DVC

## Dataset

The Iris dataset is used for this project.

The dataset is generated using Scikit-learn and stored as:

data/iris.csv

DVC is used to track the dataset while Git tracks the DVC metadata.

## DVC Workflow

1. Initialize Git repository
2. Initialize DVC
3. Create the Iris dataset
4. Track the dataset using DVC
5. Commit Version 1 using Git
6. Modify the dataset
7. Track Version 2 using DVC
8. Commit Version 2 using Git
9. Restore an earlier dataset version using Git and DVC checkout

## Dataset Versions

### Version 1

Initial Iris dataset tracked using DVC.

### Version 2

The dataset was modified by adding a `dataset_version` column with the value `v2`.

## Project Structure

DVC_Assignment/

├── data/

│   └── iris.csv

├── create_data.py

├── .dvc/

├── .dvcignore

└── README.md

## Repository

GitHub repository:

https://github.com/akashgkuradagi/DVC_Assignment