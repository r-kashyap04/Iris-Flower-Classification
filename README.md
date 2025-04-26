This project classifies Iris flowers into three species: Setosa, Versicolor, and Virginica, using **Logistic Regression**. The classification is based on features like sepal length, sepal width, petal length, and petal width. The dataset is explored and visualized, and the model’s performance is evaluated using precision, recall, and F1 score.

## Dataset

The dataset used in this project is the **Iris Dataset**, which contains 150 samples of Iris flowers, with 4 features (sepal length, sepal width, petal length, petal width) and a target variable (`species`).

## Key Steps

1. **Data Exploration and Preprocessing**:
   - Load and clean the dataset.
   - Visualize the relationships between features using **pair plots**, **box plots**, and **correlation heatmaps**.

2. **Model Building**:
   - Train a **Logistic Regression** model using the features to predict the species.

3. **Model Evaluation**:
   - Evaluate the model using **classification metrics** such as precision, recall, and F1 score.

## Technologies Used
- **Python**: Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn (Logistic Regression)
- **Jupyter Notebook** for analysis and model building

## Results

The model successfully classifies Iris flowers into their respective species. **Setosa** is the most separable species, showing clear boundaries when compared to the others.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Iris-Flower-Classification.git
   ```

2. Install the required dependencies (if applicable):
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook:
   ```bash
   jupyter notebook Iris-Flower-Classification.ipynb
   ```
