# MedicalCostsRegression

A machine learning project aimed at predicting medical costs based on demographic and lifestyle factors. This project explores multiple regression models to provide accurate predictions of healthcare expenses.

## Models

This project uses various regression models to predict healthcare costs:
1. **Polynomial Linear Regression** (`PolyLinearModel.ipynb`): Applies polynomial features to improve linear regression performance.
2. **Gradient Boosting Regression** (`GradientBoosting.ipynb`): Utilizes gradient boosting for better predictive accuracy.
3. **Random Forest Regression** (`RandomForest.ipynb`): Leverages ensemble learning to increase prediction robustness.

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/berkaykaratas07/MedicalCostsRegression.git
   cd MedicalCostsRegression
   ```
   
2. **Set up a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate         # On Linux/Mac
   venv\Scripts\activate            # On Windows
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```


## Usage

Each model can be run separately by opening the corresponding notebook in the `notebooks/` directory. Follow these steps:

1. **Open Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
2. **Select a Notebook**:
   - `PolyLinearModel.ipynb` - Polynomial Linear Regression
   - `GradientBoosting.ipynb` - Gradient Boosting Regression
   - `RandomForest.ipynb` - Random Forest Regression

3. **Run the Notebook Cells**:
   - Each notebook contains cells for data preprocessing, model training, and evaluation. Simply run the cells sequentially.

## Data

Place the dataset (e.g., `expenses.csv`) in the `data/` folder. Ensure the dataset follows the expected structure as used in the notebooks.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Scikit-Learn for model implementations
- Matplotlib for visualizations
- Jupyter for interactive analysis
 


