
# Data Science with Python - Course by Federico Garay

This repository contains comprehensive learning materials for a complete Data Science course using Python. The course covers fundamental to advanced topics in data analysis, visualization, and machine learning.

## 📚 Course Structure

The course is organized into 7 main modules (days), each building upon previous concepts:

### Day 06: Introduction to Pandas

Introduction to data manipulation using the Pandas library.

**Topics Covered:**

- DataFrames basics: creation, inspection, and manipulation
- Reading CSV files and exploring data structures
- Series objects and their operations
- Data cleaning techniques:
  - Handling missing values (`isnull()`, `dropna()`, `fillna()`)
  - Removing duplicates
  - Type conversion
- Basic operations on columns
- Filtering data with conditions
- Adding and modifying columns

**Key Files:**

- `01-data-frames.ipynb` - Introduction to DataFrames
- `03-series.ipynb` - Working with Series
- `07-clean-data.ipynb` - Data cleaning techniques
- `09-filters.ipynb` - Filtering operations
- `11-adding.ipynb` - Adding columns and rows
- `13-project.ipynb` - Integration project

**Datasets:**

- `Precipitaciones.csv` - Precipitation data
- `medallas.csv` - Medals dataset
- `weather.csv` - Weather information

---

### Day 07: Advanced Pandas Operations

Advanced data manipulation, merging, and time series operations.

**Topics Covered:**

- Sorting and grouping data
  - `sort_values()` - Single and multiple column sorting
  - `groupby()` - Aggregation operations (mean, sum, count)
- Merging DataFrames
  - `merge()` - Inner, outer, left, and right joins
  - Index-based merging
- Join operations
- Concatenation (`concat()`)
- Date and time handling
  - Creating date ranges with `pd.date_range()`
  - Date formatting with `pd.to_datetime()`
  - Date arithmetic with `Timedelta`
  - Frequency parameters (D, ME, YE, h, s)
- Data import/export (CSV, XML)
- Location-based indexing
  - `loc[]` - Label-based indexing
  - `iloc[]` - Position-based indexing

**Key Files:**

- `01-dataframes.ipynb` - DataFrame operations
- `03-ordering-grouping.ipynb` - Sorting and grouping
- `05-merging.ipynb` - Merging techniques
- `07-join.ipynb` - Join operations
- `09-concat.ipynb` - Concatenation
- `11-dates.ipynb` - Date and time operations
- `13-reads.ipynb` - Reading different file formats
- `15-loc-iloc.ipynb` - Indexing methods
- `17-project.ipynb` - Integration project

**Datasets:**

- `fechas.csv` - Date examples
- `movies.csv` - Movie database
- `spanish-stock-exchange.csv` - Stock market data
- `tienda.csv`, `tienda_2.csv` - Store sales data
- `ventas_productos.csv` - Product sales

---

### Day 08: NumPy Fundamentals

Introduction to numerical computing with NumPy.

**Topics Covered:**

- NumPy arrays creation and manipulation
  - 1D and 2D arrays
  - Array shapes and dimensions
- Array operations
  - Concatenation with `np.concatenate()`
  - Reshaping arrays with `reshape()`
  - Mathematical operations (addition, square root)
- Array indexing and slicing
- Array structure and form manipulation
- NumPy functions
  - Mathematical functions
  - Statistical functions
  - Linear algebra operations
- File I/O with NumPy
  - Reading/writing text files
  - CSV operations
- Integration with Pandas
  - Converting between NumPy arrays and DataFrames

**Key Files:**

- `06-arrays.ipynb` - Array basics
- `08-operations.ipynb` - Array operations
- `10-indexing.ipynb` - Indexing techniques
- `12-form-strucutre.ipynb` - Structure manipulation
- `14-funciones.ipynb` - NumPy functions
- `18-import-export-files.ipynb` - File operations
- `20-numpy-pandas.ipynb` - NumPy-Pandas integration
- `22-project.ipynb` - Integration project

**Datasets:**

- `array_ejm.txt` - Array examples
- `datos_meteorologicos.csv` - Meteorological data
- `valores.csv` - Sample values
- `medallas.csv` - Medals data

---

### Day 09: Data Visualization with Matplotlib

Comprehensive guide to creating visualizations using Matplotlib.

**Topics Covered:**

- Matplotlib basics
  - Figure and axes objects
  - Basic plotting with `plt.plot()`
- Plot types:
  - **Line plots** - Trend visualization
  - **Histograms** - Distribution analysis
  - **Scatter plots** - Relationship visualization
  - **Pie charts** - Proportion representation
- Customization:
  - Colors, markers, and line styles
  - Titles, labels, and legends
  - Grid configuration
  - Axis rotation and formatting
- Multiple subplots
  - `plt.subplots()` for creating subplot grids
  - Independent axis configuration
- Plot styling and themes
- Saving figures (`plt.savefig()`)

**Key Files:**

- `01-matplot.ipynb` - Matplotlib introduction
- `02-types.ipynb` - Plot types overview
- `04-lineplots.ipynb` - Line plots
- `06-histogram.ipynb` - Histograms
- `08-scatter.ipynb` - Scatter plots
- `10-pie.ipynb` - Pie charts
- `12-multi-graph.ipynb` - Multiple plots
- `14-styles.ipynb` - Styling options
- `18-project.ipynb` - Visualization project

**Datasets:**

- `Iluminacion.csv` - Illumination data
- `meteorological.csv` - Weather data
- `rains.csv` - Rainfall information
- `Ventas.csv` - Sales data

---

### Day 10: Advanced Visualization with Seaborn

Statistical data visualization using Seaborn.

**Topics Covered:**

- Seaborn introduction and themes
  - `sns.set_theme()` for styling
- Relational plots (`relplot()`)
  - Scatter and line plots
  - Hue, style, and size parameters
  - Faceting with `col` and `row`
- Distribution plots (`displot()`)
  - Histograms
  - KDE plots
  - ECDF plots
- Categorical plots (`catplot()`)
  - Bar plots
  - Box plots
  - Violin plots
  - Strip and swarm plots
- Multiple views and facet grids
- Lower-level plotting functions
  - `scatterplot()`, `lineplot()`, etc.
- Preconfiguration and styling
- Figure-level vs Axes-level functions

**Key Files:**

- `01-intro.ipynb` - Seaborn introduction
- `02-relation-stadistical-seaboen.ipynb` - Relational plots
- `03-displot.ipynb` - Distribution plots
- `04-catplot.ipynb` - Categorical plots
- `05-multiple-views.ipynb` - Facet grids
- `06-lower-level.ipynb` - Axes-level functions
- `07-preconfig.ipynb` - Configuration
- `08-figure-vs-axes.ipynb` - Understanding plot levels

---

### Day 11: Supervised Machine Learning

Introduction to supervised learning algorithms.

**Topics Covered:**

- **Linear Regression**
  - Simple and multiple linear regression
  - Model training with `sklearn.linear_model.LinearRegression()`
  - Making predictions
  - Model visualization
- **Logistic Regression**
  - Binary classification
  - Probability predictions
- **Decision Trees**
  - Tree-based classification
  - Decision boundaries
  - Tree visualization
- **Random Forests**
  - Ensemble methods
  - Feature importance
- **Model Selection**
  - Comparing algorithms
  - Cross-validation
  - Performance metrics

**Key Files:**

- `01.regresion-lineal.ipynb` - Linear regression
- `05-decision-tree.ipynb` - Decision trees
- `08-random-tress.ipynb` - Random forests
- `09-best-algorithm.ipynb` - Algorithm comparison
- `10.project.ipynb` - ML project

**Datasets:**

- `Ventas_H1.csv`, `Ventas_H2.csv` - Sales data
- `datos_seguro.csv` - Insurance data
- `nuevo_registro.txt` - Test records

---

### Day 12: Unsupervised Machine Learning

Unsupervised learning and dimensionality reduction techniques.

**Topics Covered:**

- **K-Means Clustering**
  - Cluster identification
  - Centroid calculation
  - Visualization of clusters
  - Real-world applications (penguin dataset)
- **PCA (Principal Component Analysis)**
  - Dimensionality reduction
  - Feature extraction
  - Data visualization in reduced dimensions
  - Iris dataset example
- **SVD (Singular Value Decomposition)**
  - Matrix factorization
  - Dimensionality reduction
- **Autoencoders**
  - Neural network-based dimensionality reduction
  - Feature learning
- **Automatic clustering techniques**

**Key Files:**

- `01-kmeans.ipynb` - K-Means clustering
- `03-pca.ipynb` - Principal Component Analysis
- `05-svd.ipynb` - Singular Value Decomposition
- `07-auto-encoders.ipynb` - Autoencoders
- `08-automatic-closing.ipynb` - Automatic clustering

---

## 🛠️ Technologies and Libraries

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Basic plotting and visualization
- **Seaborn** - Statistical data visualization
- **Scikit-learn** - Machine learning algorithms
- **Jupyter Notebooks** - Interactive development environment

---

## 📊 Project Structure

Each day folder contains:

- **Numbered notebooks** - Sequential lessons on specific topics
- **Exercise notebooks** - Practice problems to reinforce concepts
- **Project notebooks** - Integration projects combining multiple concepts
- **CSV/data files** - Real-world datasets for practice

---

## 🎯 Learning Path

1. **Foundation (Days 06-07)**: Master Pandas for data manipulation
2. **Numerical Computing (Day 08)**: Learn NumPy for efficient computations
3. **Visualization (Days 09-10)**: Create compelling data visualizations
4. **Machine Learning (Days 11-12)**: Apply supervised and unsupervised learning

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Running the Notebooks

```bash
jupyter notebook
```

Navigate to any day folder and open the notebooks in sequential order.

---

## 📝 Notes

- Each notebook builds upon concepts from previous ones
- Exercise notebooks (`excercise.ipynb`, `excersice.ipynb`, `execise.ipynb`) provide hands-on practice
- Project notebooks integrate multiple concepts learned throughout each module
- Real-world datasets are included for practical experience

---

## 👨‍🏫 Course Instructor

**Federico Garay**

---

## 📖 Additional Resources

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)

---

_This course provides a complete path from data manipulation fundamentals to advanced machine learning techniques, with hands-on projects and real-world datasets._
