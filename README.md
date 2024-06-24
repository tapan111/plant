# Potato Disease Classification

This project is a web application for classifying potato diseases using a pre-trained deep learning model. The app allows users to upload an image of a potato leaf, and it will predict the type of disease (if any) along with the confidence level of the prediction.

You can also access the deployed app [here](https://potatodiseaseclassification-8fszcrr4ml54czvjhv6zg5.streamlit.app/).
## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)


## Features

- Upload an image of a potato leaf
- Get predictions for potato diseases
- Display the uploaded image along with the predicted class and confidence level

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/tapan111/potato_disease_classification.git
   cd potato_disease_classification
   ```

2. Create a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Make sure you have the trained model file (`trained.keras`) in the project directory.

2. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```

3. Open your web browser and go to `http://localhost:8501` to access the app.


