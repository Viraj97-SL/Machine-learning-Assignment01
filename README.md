# Machine-learning-Assignment01
Predicting heart disease with decision tree classification
# Decision Tree Classification and Analysis

This project explores the application of decision tree classification on a given dataset. It includes data analysis, model building, evaluation, and visualization.

## Project Description

This project performs the following tasks:

1.  **Data Analysis:**
    * Exploratory data analysis (EDA) using Pandas to understand the dataset's characteristics.
    * Visualization of data distributions using Matplotlib and Seaborn (e.g., histograms, bar charts, pie charts).
    * Duplicate data handling.
2.  **Model Building:**
    * Building a decision tree classifier using Scikit-learn's `DecisionTreeClassifier`.
    * Splitting the data into training and testing sets.
    * Hyperparameter tuning using `GridSearchCV` to optimize the model and mitigate overfitting.
3.  **Model Evaluation:**
    * Evaluating the model's performance using accuracy scores.
    * Generating and visualizing a confusion matrix.
    * Generating a classification report with precision, recall, and F1-scores.
    * Analyzing feature importance.
4.  **Tree Visualization:**
    * Visualizing the decision tree using `sklearn.tree.plot_tree` for basic visualization.
    * Visualizing the decision tree using `export_graphviz` and `graphviz` for more detailed and customizable visualization.

## How to Use

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/Viraj97-SL/Machine-learning-Assignment01.git]
    cd [https://github.com/Viraj97-SL/Machine-learning-Assignment01.git]
    ```
2.  **Install Dependencies:**
    * Create a virtual environment (recommended):
        ```bash
        python -m venv venv
        source venv/bin/activate  # On macOS/Linux
        venv\Scripts\activate      # On Windows
        ```
    * Install the required Python libraries:
        ```bash
        pip install pandas scikit-learn matplotlib seaborn graphviz
        ```
    * **Install Graphviz software:**
        * You must also install the Graphviz software on your system.
        * **Windows:** Download the installer from [http://www.graphviz.org/download/](http://www.graphviz.org/download/) and add the `bin` directory to your system's PATH.
        * **macOS:** `brew install graphviz`
        * **Linux (Debian/Ubuntu):** `sudo apt-get install graphviz`
        * **Linux (Fedora/CentOS):** `sudo yum install graphviz`
3.  **Run the Jupyter Notebook:**
    * Start Jupyter Notebook:
        ```bash
        jupyter notebook
        ```
    * Open the `.ipynb` file and execute the cells.

## Dependencies

* **Python Libraries:**
    * `pandas` (for data manipulation)
    * `scikit-learn` (for machine learning)
    * `matplotlib` (for basic plotting)
    * `seaborn` (for advanced plotting)
    * `graphviz` (for decision tree visualization)

* **Graphviz Software:**
    * Graphviz is required for the advanced tree visualization. You need to install it separately according to your operating system.

## Files

* `[your-notebook-name].ipynb`: Jupyter Notebook containing the code and analysis.
* `[your-data-file].csv` or `[your-data-file].xlsx`: The dataset used in the analysis.
* `README.md`: This file.

## Notes

* Ensure that the Graphviz `bin` directory is added to your system's PATH environment variable for the `graphviz` visualization to work correctly.
* The notebook assumes that the data file is in the same directory as the notebook. Update the file paths if necessary.
* Feel free to modify the code and parameters to experiment with different settings and datasets.
