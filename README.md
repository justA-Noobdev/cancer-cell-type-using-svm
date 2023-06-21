Cell Sample Classification using Support Vector Machines (SVM)
==============================================================

This machine learning project aims to predict whether a cell sample is benign or malignant using Support Vector Machines (SVM). The project utilizes a dataset containing various features extracted from cell samples, such as cell Clump, size, and texture, to train an SVM model. The trained model can then be used to classify new cell samples as benign or malignant.

Installation and Setup
----------------------

1.  Clone the repository:

```shellCopy code
git clone https://github.com/justA-Noobdev/cancer-cell-type-using-svm.git
```

1.  Install the required dependencies:

```shellCopy code
pip install scikit-learn matplotlib seaborn
```

1.  Open the notebook:

-   Launch Jupyter Notebook or JupyterLab.
-   Navigate to the cloned repository directory.
-   Open the notebook file `cell_classification.ipynb`.

Usage
-----

1.  Run the notebook:

    -   Execute each cell in the notebook sequentially.
    -   The notebook contains step-by-step instructions and code comments to guide you through the process.
  
2.  Evaluation Metrics and Confusion Matrix:

    -   The notebook includes code to calculate the F1 score and Jaccard score.
    -   To plot a confusion matrix, run the provided code snippet in a separate cell after training and evaluating the model.

Directory Structure
-------------------

-   `SVM.ipynb`: Jupyter Notebook containing the entire project code.
-   `cell_samples.csv`: File for the dataset (included in this repository).

Feel free to modify and extend this project as needed. If you encounter any issues or have questions, please open an issue in the repository.

License
-------

This project is licensed under the MIT License. See the [LICENSE](https://chat.openai.com/LICENSE) file for more details.
