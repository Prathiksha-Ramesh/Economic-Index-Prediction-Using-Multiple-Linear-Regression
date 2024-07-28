# Economic Index Prediction Using Multiple Linear Regression

This project demonstrates a multiple linear regression analysis using Python. The project uses an economic index dataset to predict target variables based on multiple features.

## Project Structure

- `multiple-linear-regression.ipynb`: Jupyter notebook containing the code for the multiple linear regression analysis.
- `requirements.txt`: List of Python libraries required to run the project.
- `economic_index.csv`: Dataset containing economic index data used for the regression analysis.
- `LICENSE`: MIT License for the project.

## Prerequisites

Make sure you have Python installed on your machine. You can download Python from [python.org](https://www.python.org/).

## Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/prathiksha-ramesh/economic-index-prediction.git
    ```

2. Navigate to the project directory:

    ```bash
    cd economic-index-prediction
    ```

3. Install the required libraries by running:

    ```bash
    pip install -r requirements.txt
    ```

## Running the Project

1. Open the Jupyter notebook:

    ```bash
    jupyter notebook multiple-linear-regression.ipynb
    ```

2. Run the cells in the notebook to see the multiple linear regression analysis.

## Dataset

The dataset `economic_index.csv` contains the following columns:

- `year`: The year the data was recorded.
- `month`: The month the data was recorded.
- `interest_rate`: The interest rate in percentage.
- `unemployment_rate`: The unemployment rate in percentage.
- `index_price`: The economic index value to be predicted.

## Project Steps

1. **Data Loading**: Load the dataset using pandas.
2. **Data Visualization**: Visualize the data using matplotlib and seaborn.
3. **Preprocessing**: Handle any missing values, encode categorical variables, and prepare the data for modeling.
4. **Modeling**: Perform multiple linear regression using scikit-learn.
5. **Evaluation**: Evaluate the model's performance using appropriate metrics.
6. **Prediction**: Use the model to predict economic index values based on new input data.

## Dependencies

The project requires the following libraries, as specified in `requirements.txt`:

- pandas
- numpy
- matplotlib
- scikit-learn
- seaborn

You can install these dependencies using the command mentioned in the Installation section.

## Contributing

If you wish to contribute to this project, please create a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments

This project is inspired by common examples of multiple linear regression analysis used in data science tutorials and from the udemy course.
