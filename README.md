# MNIST


```markdown
# Logistic Regression for Digit Classification (MNIST Dataset)

This repository contains Python code for training a Logistic Regression model to classify digits using the MNIST dataset. The MNIST dataset consists of images of handwritten digits from 0 to 9.

## Contents

1. **Data Loading and Preprocessing:**
    - The code loads the training data from the `train.csv` file and extracts features (pixels) and labels.
    - It splits the data into training and validation sets using scikit-learn's `train_test_split`.
    - Standardization is applied to the feature vectors using `StandardScaler`.

2. **Model Training:**
    - A Logistic Regression model is trained using scikit-learn's `LogisticRegression` class with a specified maximum number of iterations.

3. **Model Evaluation:**
    - The code evaluates the model's performance on the validation set, calculating accuracy and providing a classification report.

4. **Making Predictions:**
    - The trained model is used to make predictions on the test data.
    - The predictions are saved in a submission file in a specified format.

5. **Visualization:**
    - The code includes a visualization section that displays a random selection of digit images from the validation set along with their predicted labels.

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/logistic-regression-mnist.git
   ```

2. Navigate to the project directory:
   ```bash
   cd logistic-regression-mnist
   ```

3. Run the Python script to train the Logistic Regression model and make predictions on digit images:
   ```bash
   python logistic_regression_mnist.py
   ```

4. View the results, including accuracy and classification report, in the script's output.

5. Check the `submission.csv` file for the model's predictions on the test data.

6. Explore the visualizations of randomly selected digit images from the validation set in the script's output.

## Dependencies

Ensure you have the required Python libraries installed. You can install them using the following commands:

```bash
pip install pandas
pip install numpy
pip install scikit-learn
pip install matplotlib
```

## Data

The training data is loaded from the `train.csv` file. Ensure you have the dataset available in the project directory or update the file path as needed.

## License

This project is open-source and available under the [MIT License](LICENSE).

---

This code demonstrates how to train a Logistic Regression model for digit classification using the MNIST dataset. Feel free to modify it for different datasets or experiment with various machine learning algorithms for image classification tasks.

If you encounter any issues or have questions, please feel free to open an issue or contact the project maintainers.

Happy digit classification!
```
