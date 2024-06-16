# Iris Classification Task

This project demonstrates the classification of Iris flowers using three different machine learning algorithms: Random Forest, Decision Tree, and K-Nearest Neighbors (KNN).

## Dataset

The Iris dataset is a well-known dataset in the machine learning community, containing measurements of Iris flowers' sepal and petal lengths and widths, along with their corresponding species (setosa, versicolor, or virginica).

### Features

- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

### Target

- Species: Iris species (setosa, versicolor, virginica)

## Algorithms Used

1. **Random Forest**:
   - Ensemble learning method that constructs multiple decision trees during training and outputs the mode of the classes as the prediction.

2. **Decision Tree**:
   - A decision tree recursively splits the dataset into subsets based on the most significant attribute at each node, resulting in a tree-like structure where leaf nodes represent class labels.

3. **K-Nearest Neighbors (KNN)**:
   - Instance-based learning method that classifies objects based on the majority class among its k nearest neighbors in the feature space.

## Implementation

### Libraries Used

- `numpy`: For numerical operations.
- `pandas`: For data manipulation and analysis.
- `scikit-learn`: For machine learning algorithms and utilities.
- `matplotlib`: For plotting visualizations.
- `seaborn`: For enhancing the aesthetics of matplotlib plots.

### Files

- **iris.csv**: CSV file containing the Iris dataset.
- **Iris_Classification.ipynb**: Jupyter Notebook demonstrating the implementation and evaluation of Random Forest, Decision Tree, and KNN classifiers on the Iris dataset.
- **README.md**: This file, providing an overview of the project.

### Usage

1. Clone the repository:

   ```
   git clone https://github.com/hemantkumar0077/Iris-Classification.git
   ```

2. Navigate to the project directory:

   ```
   cd Iris-Classification
   ```

3. Open and run `Iris_Classification.ipynb` in Jupyter Notebook or any compatible environment.

4. Follow the instructions in the notebook to execute each cell and observe the results of training, testing, and evaluating the classifiers.

### Results

- The notebook includes visualizations of the dataset, performance metrics (accuracy, confusion matrix), and comparisons between the three classifiers.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Iris dataset: Fisher, R.A. "The use of multiple measurements in taxonomic problems" Annual Eugenics, 7, Part II, 179-188 (1936); also in "Contributions to Mathematical Statistics" (John Wiley, NY, 1950).
