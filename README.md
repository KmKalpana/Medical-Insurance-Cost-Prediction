# Medical Insurance Cost Prediction

This project aims to predict medical insurance costs based on various features using a linear regression model. The code provided performs the following steps:

1. Data Collection and Analysis:
   - Loads the insurance data from a CSV file into a Pandas DataFrame.
   - Displays the first five rows of the DataFrame.
   - Retrieves the shape and information of the dataset.
   - Checks for missing values in the dataset.
   - Provides statistical measures and distributions for different columns using visualizations.

2. Data Pre-Processing:
   - Encodes categorical features (sex, smoker, and region) into numerical values using label encoding.

3. Splitting the Data:
   - Splits the dataset into training and testing sets using a 80:20 ratio.

4. Linear Regression:
   - Trains a linear regression model on the training data.
   - Evaluates the model's performance using the R-squared metric on both training and testing data.

5. Building a Predictive System:
   - Provides an example of using the trained model to predict insurance costs based on user-provided input.

## Prerequisites

To run the code, you need to have the following libraries installed:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn (sklearn)

## Usage

1. Make sure the required libraries are installed.
2. Download the insurance dataset in CSV format and save it as 'insurance.csv' in the same directory as the code file.
3. Run the code.
4. The code will display visualizations of the dataset and print the R-squared values for the training and testing data.
5. To use the predictive system, modify the `input_data` variable with the desired values and run the code again. The predicted insurance cost will be displayed.

Note: The code assumes that the insurance dataset is in the correct format with the expected column names.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

Feel free to modify and use the code according to your needs.

## Acknowledgments

- The insurance dataset used in this project is for demonstration purposes and can be obtained from various sources.
- The code is inspired by various machine learning tutorials and examples.
