
# Fake News Detection using Machine Learning

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)

## Introduction

This repository contains a comprehensive project for detecting fake news using machine learning techniques. The project includes data analysis, model training, and a web application for real-time fake news detection. The machine learning model is designed to classify news articles as either real or fake based on their content.

## Project Structure

The repository is organized into the following directories and files:

- **Images**: Contains important project images, such as block diagrams, classification reports, confusion matrices, and screenshots.
- **dataset**: Includes the dataset, consisting of train and test data from Kaggle, which is used to train and test the model.
- **static**: Houses static assets for the web application, including CSS, JavaScript, etc.
- **templates**: Includes HTML templates for the web application, such as `Landingpage.html` and `prediction page.html`.
- **Fake_News_Detector-PA.ipynb**: Jupyter Notebook file for data analysis and model training.
- **app.py**: Flask web application for real-time fake news detection.
- **model.pkl**: Pre-trained machine learning model for fake news detection.
- **vector.pkl**: Pre-trained vectorizer for text data.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/abiek12/Fake-News-Detection-using-MachineLearning.git
   ```

2. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv my_env
   ```

3. Activate the virtual environment:

   ```bash
   # On Windows
   .\my_env\Scripts\Activate.ps1
   # On macOS and Linux
   source my_env/bin/activate
   ```

4. Install project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Run the web application:

   ```bash
   python app.py
   ```
Access the application in your web browser by navigating to `http://localhost:5000`.

---

