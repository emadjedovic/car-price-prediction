# Car Price Prediction

This project aims to predict car prices based on various features using machine learning techniques.

The data is scraped from OLX and preprocessed to create a clean dataset for training and testing machine learning models.

## Project Structure
```
├── article_urls.txt
├── car_data.csv
├── cleaned_car_data.csv
├── data_preprocessing.ipynb
├── main.ipynb
├── model_training.ipynb
├── README.md
└── requirements.txt
```

- `article_urls.txt`: Contains the URLs of individual car listings.
- `car_data.csv`: Contains the raw scraped car data.
- `cleaned_car_data.csv`: Contains the cleaned and preprocessed car data.
- `data_preprocessing.ipynb`: Contains the code for cleaning and preprocessing the scraped data.
- `main.ipynb`: Contains the code for web scraping car data from OLX.
- `model_training.ipynb`: Contains the code for training and evaluating machine learning models.
- `README.md`: Project documentation.
- `requirements.txt`: List of Python packages required for the project.

## Setup

To set up the project, follow these steps:

1. Clone the repository:
```cd
git clone https://github.com/emadjedovic/car-price-prediction
```
2. Navigate to the project directory:
```cd
cd car-price-prediction
```
3. Install the required packages:
``` cd
pip install -r requirements.txt
```

## Data Scraping

The `main.ipynb` notebook contains the code for scraping car data from OLX.
It uses Selenium to navigate through the website and extract relevant information.
The URLs of individual car listings are saved in `article_urls.txt`.
The car data is saved to to `car_data.csv`.

## Data Preprocessing

The `data_preprocessing.ipynb` notebook contains the code for cleaning and preprocessing the scraped data.
It includes steps for handling missing values, encoding categorical variables, and scaling numerical features.
The cleaner car data is saved to `cleaned_car_data.csv`.

## Model Training

The `model_training.ipynb` notebook contains the code for training and evaluating machine learning models.

- **Neural Network**: Trained using Keras, evaluated using Mean Absolute Error (MAE).
- **Linear Regression**: Trained using scikit-learn, evaluated using Mean Absolute Error (MAE).

The models are evaluated on a test set, and their performance is visualized using plots.
