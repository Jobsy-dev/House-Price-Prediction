# House Price Prediction Project

This is a Python project that allows user to train a model to with various house parameters and receive a predicted house price using a trained machine learning model.

## Requirements

Make sure you have Python installed (Python 3.7 or later recommended). Install the necessary dependencies by running:

```bash
pip install joblib scikit-learn numpy
```

## Project Structure

```
/house-price-prediction
├── best_house_price_model_5features.pkl  # Pre-trained model file
├── main.ipynb              # Main script for model building
├── README.md               # Documentation

```

## How to Use

1. Ensure that `House Dataset.xlsx` (Dataset) is in the project directory.
2. Run the script:
main.ipynb

3. Test the Model

```
Enter Wall Area (m²): 120
Enter Roof Area (m²): 100
Enter Inner Walls Area (m²): 80
...
```

## Features
- Uses the main.ipynb to train the model based on the dataset provided.
- Uses a pre-trained machine learning model to make predictions

## Model Information
The trained model (`best_house_price_model_5features.pkl`) should be created using `scikit-learn`. Ensure the input feature order matches the expected format when training the model.

The trained model (`best_house_price_model.pkl`) is the model that has 10 best features for more detailed predictions, along with the (`scaler.pkl`)


## License
This project is licensed under the MIT License.

---

For any issues, feel free to contribute or raise a pull request!

