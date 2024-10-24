# House Price Predictor

## Overview

The House Price Predictor is a web application built using Flask and machine learning techniques to predict house prices specifically for properties located in Bangalore. Users can input details such as location, number of bedrooms (BHK), number of bathrooms, and total square footage to receive an estimated price prediction.

## Features

- **User-Friendly Interface**: Built with Bootstrap for a responsive and clean design.
- **Location-Based Predictions**: Users can select from various locations within Bangalore for accurate price predictions.
- **Real-Time Predictions**: The app predicts the price of a house instantly after the user submits their information.

## Technologies Used

- **Flask**: A lightweight WSGI web application framework.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Pickle**: For loading the pre-trained machine learning model.
- **Bootstrap**: For responsive web design.

## Installation

To set up this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Hussainaakash11/BangaloreHouse-PricePredictor
   cd <repository-directory>
   ```

2. **Create a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages**:
   Ensure you have a `requirements.txt` file in your project directory. Then run:
   ```bash
   pip install -r requirements.txt
   ```

4. **Download the model and data**:
   Ensure you have the `RidgeModel.pkl` and `Cleaned_data.csv` files in your project directory.

5. **Run the application**:
   ```bash
   python main.py
   ```

6. **Access the application**: Open your web browser and go to `http://127.0.0.1:5000/`.

## Usage

1. **Select the Location**: Choose the location of the property from the dropdown menu (specific to Bangalore).
2. **Enter Details**:
   - Input the number of BHK (bedrooms).
   - Input the number of bathrooms.
   - Enter the total square footage of the property.
3. **Predict Price**: Click on the "Predict Price" button to get the estimated price for the property.

## Contributing

Contributions are welcome! If you would like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push to your branch.
4. Open a pull request.

## Acknowledgments

- Thanks to the developers and contributors of Flask, Pandas, and Bootstrap for making this project possible.
