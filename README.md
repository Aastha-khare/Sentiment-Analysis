
# Sentiment Analysis on Amazon Reviews

## Project Overview
This project focuses on sentiment analysis of Amazon product reviews. It involves:

1. **Web Scraping**: Collecting Amazon product reviews.
2. **Exploratory Data Analysis (EDA)**: Understanding the dataset through visualizations and statistics.
3. **Text Processing & Modeling**: Preprocessing text data and building sentiment analysis models.

## Project Structure
```
├── Amazon Reviews Web Scraping.py  # Script for scraping Amazon reviews
├── Amazon Reviews EDA and Visualizations.ipynb  # EDA and data visualization
├── Amazon Reviews Text Processing and Modeling.ipynb  # NLP processing and model training
├── model.py  # Script for saving and loading the trained model
├── requirements.txt  # List of dependencies
├── README.md  # Project documentation
```

## Installation
To set up the project, follow these steps:

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```
2. **Create a virtual environment (optional but recommended)**:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. **Install dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
### 1. Web Scraping
Run the `Amazon Reviews Web Scraping.py` script to collect Amazon product reviews:
```sh
python Amazon Reviews Web Scraping.py
```

### 2. Exploratory Data Analysis
Open `Amazon Reviews EDA and Visualizations.ipynb` in Jupyter Notebook:
```sh
jupyter notebook
```

### 3. Text Processing & Modeling
Execute `Amazon Reviews Text Processing and Modeling.ipynb` to preprocess text and train sentiment models.

### 4. Model Prediction
Use `model.py` to load the trained model and make predictions on new reviews.

## Dependencies
All dependencies are listed in `requirements.txt`. You can install them using:
```sh
pip install -r requirements.txt
```

## Contributing
Feel free to fork this repository and submit pull requests for improvements.

## License
MIT License

