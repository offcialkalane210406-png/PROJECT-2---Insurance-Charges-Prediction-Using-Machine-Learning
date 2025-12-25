# PROJECT-2---Insurance-Charges-Prediction-Using-Machine-Learning
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Insurance Charges Prediction Using Machine Learning</title>
</head>
<body>

<h1>Insurance Charges Prediction Using Machine Learning</h1>

<h2>Project Overview</h2>
<p>
This project focuses on predicting insurance charges using regression-based Machine Learning techniques.
The complete end-to-end workflow was implemented in a Jupyter Notebook environment, covering
data understanding, exploratory data analysis (EDA), data preprocessing, feature engineering,
model training, and evaluation.
</p>

<p>
The objective of this project is to analyze how factors such as age, BMI, smoking habits,
number of children, gender, and region influence insurance costs, and to build a regression
model that can accurately predict insurance charges.
</p>

<h2>Dataset Description</h2>
<p>
The dataset contains demographic and health-related attributes of individuals along with
their corresponding insurance charges. Both numerical and categorical features are present.
</p>

<ul>
    <li>Age</li>
    <li>Sex</li>
    <li>BMI</li>
    <li>Number of children</li>
    <li>Smoking status</li>
    <li>Region</li>
    <li>Insurance charges (target variable)</li>
</ul>

<h2>Exploratory Data Analysis (EDA)</h2>
<p>
Detailed exploratory data analysis was performed to understand data distributions,
detect skewness, identify outliers, and analyze relationships between independent variables
and insurance charges.
</p>

<ul>
    <li>Distribution analysis using histograms and density plots</li>
    <li>Comparison of insurance charges across smokers and non-smokers</li>
    <li>Impact analysis of age and BMI on insurance costs</li>
    <li>Categorical feature analysis using count plots</li>
    <li>Correlation analysis to identify influential features</li>
</ul>

<h2>Data Preprocessing</h2>
<ul>
    <li>Checking and handling missing values</li>
    <li>Outlier analysis and treatment</li>
    <li>Encoding categorical variables (sex, smoker, region)</li>
    <li>Feature scaling where required</li>
    <li>Preparing clean datasets for model training</li>
</ul>

<h2>Feature Engineering</h2>
<p>
Relevant features were selected and transformed based on correlation analysis and EDA insights
to improve model performance and interpretability.
</p>

<h2>Model Development</h2>
<p>
Regression models were developed using the scikit-learn library.
The dataset was split into training and testing sets to evaluate generalization performance.
</p>

<ul>
    <li>Train-test data split</li>
    <li>Regression model training</li>
    <li>Performance comparison</li>
</ul>

<h2>Model Evaluation</h2>
<p>
Model performance was evaluated using standard regression metrics.
</p>

<ul>
    <li>R² Score</li>
    <li>Adjusted R² Score</li>
</ul>

<p>
The final model achieved an accuracy of approximately <strong>79%</strong>,
indicating good predictive capability on unseen data.
</p>

<h2>Technologies Used</h2>
<ul>
    <li><strong>Programming Language:</strong> Python</li>
    <li><strong>Environment:</strong> Jupyter Notebook</li>
    <li><strong>Libraries:</strong>
        <ul>
            <li>Pandas</li>
            <li>NumPy</li>
            <li>Matplotlib</li>
            <li>Seaborn</li>
            <li>scikit-learn</li>
        </ul>
    </li>
</ul>

<h2>Project Workflow</h2>
<ol>
    <li>Importing required libraries</li>
    <li>Loading and understanding the dataset</li>
    <li>Exploratory Data Analysis (EDA)</li>
    <li>Data cleaning and preprocessing</li>
    <li>Feature engineering and encoding</li>
    <li>Train-test split</li>
    <li>Model training</li>
    <li>Model evaluation using R² and Adjusted R²</li>
</ol>

<h2>Key Learnings</h2>
<ul>
    <li>Understanding real-world regression problems</li>
    <li>Analyzing the impact of health and lifestyle factors on insurance costs</li>
    <li>Hands-on experience with EDA and visualization techniques</li>
    <li>Practical implementation of regression models using scikit-learn</li>
    <li>Interpreting R² and Adjusted R² metrics</li>
</ul>

<h2>Future Enhancements</h2>
<ul>
    <li>Applying advanced regression algorithms</li>
    <li>Hyperparameter tuning</li>
    <li>Feature selection optimization</li>
    <li>Deploying the model as a web application</li>
</ul>

<h2>Acknowledgements</h2>
<p>
Learning support and structured guidance from
<strong>Sheryians AI School (YouTube)</strong>
played an important role in completing this project.
</p>

<h2>Author</h2>
<p>
<strong>Jagdish Kalane</strong><br>
Machine Learning and Data Science Enthusiast<br>
Open to feedback, suggestions, and collaboration.
</p>

<hr>

<p>
<strong>Note:</strong> This repository is intended for learning, practice,
and portfolio demonstration purposes.
</p>

</body>
</html>
