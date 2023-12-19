# Real Estate Price Prediction

Real Estate Price Prediction is a machine learning project that leverages Linear Regression to predict house prices based on various features. This project is valuable for investors, developers, and homeowners, providing insights for informed decision-making and investment planning.

## Dataset

The dataset contains 414 entries with detailed information on real estate transactions. Each entry includes the following features:

- **Transaction Date**: Date of the property transaction.
- **House Age**: Age of the property in years.
- **Distance to the Nearest MRT Station**: Proximity to the nearest Mass Rapid Transit station in meters, indicating convenience and accessibility.
- **Number of Convenience Stores**: Count of convenience stores in the vicinity, reflecting the property’s accessibility to basic amenities.
- **Latitude and Longitude**: Geographical coordinates of the property, defining its location.
- **House Price of Unit Area**: The target variable representing the house price per unit area.

## Project Overview

The project involves using a Linear Regression model to predict house prices based on the provided dataset. The model is trained on historical real estate transactions, learning the relationships between various features and the house price of unit area. This trained model can then be used to make predictions on new data.

## File Structure

The repository is organized as follows:

- **`Real_Estate.csv`**: The dataset file containing real estate transaction information.
- **`Real_Estate_Prediction.ipynb`**: Jupyter Notebook containing the Python code for data exploration, model training, and predictions.
- **`images/`**: Images used in the project, such as bg or results.
- **`database_setup.sql`**: SQL file with the database setup for storing prediction results.
- **`README.md`**: This file, providing an overview of the project, dataset, and file structure.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/real-estate-price-prediction.git
   cd real-estate-price-prediction
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook:**
   Open and run the `Real_Estate_Prediction.ipynb` notebook to explore the data, train the model, and make predictions.

## Usage

The project demonstrates how to use Linear Regression for real estate price prediction. The Jupyter Notebook provides step-by-step guidance on data preprocessing, model training, and prediction.

## Database Setup

The `database_setup.sql` file contains the SQL code for setting up a database to store prediction results. Make sure to run this script before making predictions if you want to store results in a database.

```bash
mysql -u root -p house < database_setup.sql
```

## Demo

For a quick demonstration, please refer to the `demo/README.md` file.

## License

This project is licensed under the [MIT License](LICENSE).



## Acknowledgments

Special thanks to AMAN KHARWAL for his valuable contributions and insights throughout the development of this project.
visit [thecleverprogrammer](https://thecleverprogrammer.com/)


## Contact

For inquiries, suggestions, or collaboration opportunities, feel free to reach out:

- **Hiran Joseph**
  - Email: [Hiran](hiranvjoseph@gmail.com)
  - LinkedIn: [Hiran Joseph](https://www.linkedin.com/in/hiranjoe/)
  - Kaggle: [@Hiran Joe ](https://www.kaggle.com/hiranjoseph)
