# Housing-Price-Prediction

This project performs an in-depth Exploratory Data Analysis (EDA) on a housing dataset to understand key patterns and insights related to house prices. It uses pandas, matplotlib, and seaborn to clean, analyze, and visualize the data.

**📁 Dataset**
The dataset used in this project is loaded from an Excel file named HousePricePrediction.xlsx. It includes various numerical and categorical features related to properties, such as lot size, building type, condition, and sale price.

**📊 Key Steps in the Analysis**
1. Data Loading and Inspection
Load the dataset using pandas.

Preview the first few rows with .head().

Check dataset structure and types with .info().

2. Feature Classification
Identify and count:

Categorical features (object type)

Integer features

Float features

3. Data Cleaning
Drop the Id column as it doesn't carry predictive value.

Fill missing values in SalePrice with the mean.

Drop rows with remaining missing values.

4. Univariate Analysis
Plot the distribution of SalePrice using a histogram.

Explore categorical features with countplot (first 5 categories).

5. Correlation Analysis
Compute and visualize the top 10 features most correlated with SalePrice using a heatmap.

6. Bivariate & Multivariate Visualizations
Boxplot of SalePrice vs. OverallCond

Scatter plot of LotArea vs. SalePrice

Pairplot of top correlated numerical features

Violin plot of SalePrice by BldgType

Bar chart of average SalePrice by Neighborhood

**📷 Visualizations Included**
Histogram of sale prices

Heatmap of feature correlations

Boxplot, Scatterplot, Violin Plot

Countplots of categorical variables

Pairplot of important numerical features

Barplot of average sale prices per neighborhood

**🛠️ Libraries Used**
pandas – Data manipulation

matplotlib – Basic plotting

seaborn – Statistical visualization

**📎 How to Run**
Make sure you have Python installed.

Install required libraries:

bash
Copy
Edit
pip install pandas matplotlib seaborn openpyxl
Place the HousePricePrediction.xlsx file in the project directory.

Run the script in a Python environment (e.g., Jupyter Notebook or any IDE).

**📈 Future Improvements**
Feature engineering and encoding for model building

Building a regression model to predict house prices

Outlier detection and advanced imputation

**🧑‍💻 Author**
Vaishali Khandelwal – Data Analyst / Enthusiast

LinkedIn [www.linkedin.com/in/vaishali-khandelwal-24099a187]

📄 License
This project is open-source and available under the MIT License.
