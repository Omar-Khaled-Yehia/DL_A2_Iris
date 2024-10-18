# Iris Species Classification using PyTorch
## Objective
The goal of this project is to build a multiclass classification model using PyTorch to classify iris species based on four features (sepal length, sepal width, petal length, and petal width). The species can belong to one of the three classes: Iris-setosa, Iris-versicolor, and Iris-virginica. The target accuracy is +95%, with a comprehensive evaluation using metrics such as Accuracy, Precision, Recall, F1-Score, and the ROC-AUC curve (One-vs-Rest strategy for multiclass).

## Dataset Description
The Iris dataset contains 150 samples of iris flowers with the following columns:

1. Sepal Length (cm)
2. Sepal Width (cm)
3. Petal Length (cm)
4. Petal Width (cm)
5. Species (Target variable with 3 classes: Iris-setosa, Iris-versicolor, Iris-virginica)

## Steps to Run the Code
1. Clone the repository:
git clone https://github.com/your-username/iris-pytorch-classification.git
cd iris-pytorch-classification
2. Install the required dependencies (see instructions below).
3. Run the code in a Jupyter Notebook:
jupyter notebook
4. Open the provided notebook and execute all cells to preprocess the data, build, train, and evaluate the model.

## Dependencies and Installation Instructions
Ensure you have Python installed, then install the dependencies using pip:
pip install -r requirements.txt

You can create a virtual environment and install the dependencies by running:
python -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`
pip install -r requirements.txt

## Model Evaluation
The model is evaluated using the following metrics:

1. Accuracy: Measures the overall correctness of the model's predictions.
2. Confusion Matrix: Shows the distribution of correct and incorrect predictions across all classes.
3. Precision, Recall, and F1-Score: Provide insights into the model's performance for each class.
4. ROC-AUC: Calculated using the One-vs-Rest strategy to evaluate how well the model separates each class.

In addition, the training process is visualized through loss plots, and ROC curves are plotted for each class.

