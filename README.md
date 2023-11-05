# Project README

## Overview
This repository contains datasets and Jupyter notebooks related to the development of a recommendation system for the Steam gaming platform. The project is structured into two main directories: `data` and `notebooks`.

## Repository Structure

### `data/`
This directory contains all the datasets used and generated during the project:

- `games_filtered.csv`: A cleaned and processed dataset containing key information about games after initial data analysis and refinement.
- `steam.csv`: The original, comprehensive dataset of Steam games, including all collected attributes and records.
- `user.csv`: The raw user data capturing interactions (purchases and playtime) with Steam games.
- `users_filtered.csv`: A filtered version of the user data, retaining only relevant interactions for further analysis and modeling.

### `notebooks/`
This directory hosts the Jupyter notebooks which detail the project's progression through various stages:

1. `1-Data_Analysis.ipynb`: The initial exploratory data analysis notebook that examines the datasets, identifies patterns, and makes preliminary observations.
2. `2-Data_Refinement.ipynb`: This notebook focuses on cleaning and refining the data, preparing it for the feature engineering and modeling stages.
3. `3-Recommendation System.ipynb`: The final notebook where the recommendation system is constructed, trained, and evaluated using the processed data.

## Usage
To utilize this repository:

1. Clone the repo to your local machine or download the files directly.
2. Ensure you have Jupyter Notebook or JupyterLab installed to open `.ipynb` files.
3. Datasets in the `data/` directory can be explored or manipulated using any data analysis tools or libraries such as pandas in Python.
4. Recommend to sequentially go through the notebooks in the `notebooks/` directory to understand the project's flow and methodology.

