# 🐧 Penguin Species Prediction App

Welcome to the **Penguin Species Prediction App**, a machine learning application built with **Streamlit** and powered by **RandomForestClassifier** from Scikit-learn. This app predicts the species of penguins based on their physical features.

## Overview

This app allows users to:
- Input features like island, bill length, bill depth, flipper length, body mass, and gender of a penguin.
- View real-time predictions of the penguin species (*Adelie, Chinstrap, Gentoo*).
- Visualize the dataset and model predictions interactively.

## Features

- **Data Exploration**: View the raw dataset and visualize the distribution of penguins based on different features.
- **Interactive Inputs**: Adjust sliders and dropdowns in the sidebar to provide input data for prediction.
- **Model Training**: The app trains a **Random Forest Classifier** on the penguin dataset and performs predictions on user input.
- **Prediction Output**: Displays the probability distribution across the species and highlights the predicted species.

## How it Works

1. The app loads the **penguins_cleaned.csv** dataset.
2. Users select input features via the Streamlit sidebar.
3. The input features are processed, and a Random Forest model predicts the penguin species.
4. The app displays both the predicted species and the confidence probabilities.

## Requirements

- **Python 3.x**
- **Streamlit**
- **Scikit-learn**
- **Pandas**
- **Numpy**

## How to Run the App

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/penguin-species-prediction-app.git
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

4. Open the app in your browser at `http://localhost:8501`.

## Dataset

The app uses the **Penguins Cleaned Dataset** available [here](https://raw.githubusercontent.com/dataprofessor/data/master/penguins_cleaned.csv).

## Demo

![App Demo](screenshot.png)

## Future Work

- Add more advanced machine learning models.
- Expand dataset features.
- Improve model interpretability and visualization.

Feel free to contribute by opening a pull request!

## License

This project is licensed under the MIT License.

---

**Author:** FARUQ AFOLABI
