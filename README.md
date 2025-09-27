1. **Libraries & Data Import**

   * Imported `numpy`, `pandas`, and `matplotlib`.
   * Loaded the dataset `Titanic-Dataset.csv` into a DataFrame.

2. **Initial Exploration**

   * Looked at the first few rows (`head()`), checked columns, and reviewed dataset info (`info()`).
   * Dropped the `Cabin` column.
   * Identified and handled missing values (dropped rows with `NaN` to create a cleaned dataset `df1`).

3. **Exploratory Data Analysis (EDA)**

   * Checked survival distribution and plotted bar charts (e.g., survival counts by `SibSp` – number of siblings/spouses aboard).
   * Created visualizations to understand relationships between features and survival.

4. **Data Preprocessing**

   * Converted categorical data into numeric form (likely encoding `Sex`, `Embarked`, etc.).
   * Split the dataset into features (X) and target (`Survived`).
   * Scaled/normalized data if needed.

5. **Modeling**

   * Trained machine learning models with Random Forest Classifier.
   * Evaluated it with using metrics like accuracy, precision, recall, and confusion matrix.
