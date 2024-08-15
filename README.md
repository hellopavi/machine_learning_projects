<h1>Machine Learning Projects</h1>

<p>This repository contains various machine learning projects that I have worked on. Each project is self-contained and includes the necessary code, datasets, and documentation to understand and replicate the results.</p>

<h2>Table of Contents</h2>
<ul>
    <li><a href="#introduction">Introduction</a></li>
    <li><a href="#projects">Projects</a>
        <ul>
            <li><a href="#1-salary-classification-using-k-nearest-neighbors-knn">1. Salary Classification using K-Nearest Neighbors (KNN)</a></li>
            <li><a href="#2-bank-loan-prediction-using-logistic-regression">2. Bank Loan Prediction using Logistic Regression</a></li>
           <li> <a href=#3-digit-classification-using-Support-Vector-Machine-svm> 3. Digit Classification using Support Vector Machine (SVM)</a></li>
        </ul>
    </li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#contributing">Contributing</a></li>
</ul>

<h2 id="introduction">Introduction</h2>
<p>This repository showcases my journey in machine learning through various projects. Each project focuses on a different machine learning algorithm or technique, and the aim is to apply these methods to solve real-world problems.</p>

<h2 id="projects">Projects</h2>

<h3 id="1-salary-classification-using-knn">1. Salary Classification using K-Nearest Neighbors (KNN)</h3>
<p><strong>Objective</strong>: Classify individuals' income levels (<=50K or >50K) based on features like age, education, occupation, etc.</p>
<ul>
    <li><strong>Algorithm</strong>: K-Nearest Neighbors (KNN)</li>
    <li><strong>Tools</strong>: Python, Pandas, NumPy, scikit-learn, Matplotlib</li>
    <li><strong>Dataset</strong>: salary.csv</li>
    <li><strong>Key Features</strong>:
        <ul>
            <li>Data Preprocessing: Encoding categorical variables and feature scaling.</li>
            <li>Model Training: Finding the optimal K value by analyzing error rates.</li>
            <li>Evaluation: Model accuracy and error analysis.</li>
        </ul>
    </li>
</ul>
<p>For more details, refer to the <a href="https://github.com/hellopavi/machine_learning_projects/tree/main/salary_estimation">project folder</a>.</p>

<h3 id="2-bank-loan-prediction-using-logistic-regression">2. Bank Loan Prediction using Logistic Regression</h3>
<p><strong>Objective</strong>: Predict whether a bank loan will be approved based on customer details.</p>
<ul>
    <li><strong>Algorithm</strong>: Logistic Regression</li>
    <li><strong>Tools</strong>: Python, Pandas, NumPy, scikit-learn</li>
    <li><strong>Dataset</strong>: loan_data.csv</li>
    <li><strong>Key Features</strong>:
        <ul>
            <li>Data Preprocessing: Handling missing values and encoding categorical variables.</li>
            <li>Model Training: Building a logistic regression model to predict loan approval.</li>
            <li>Evaluation: Model accuracy, confusion matrix, and ROC curve analysis.</li>
        </ul>
    </li>
</ul>
<p>For more details, refer to the <a href="https://github.com/hellopavi/machine_learning_projects/tree/main/bank_loan_prediction">project folder</a>.</p>


<h3 id="3-digit-classification-using-support-vector-machine-svm">3. Digit Classification using Support Vector Machine (SVM)</h3>
<p><strong>Objective</strong>: Classify handwritten digits (0-9) using SVM on the <code>digits</code> dataset from <code>scikit-learn</code>.</p>
<ul>
    <li><strong>Algorithm</strong>: Support Vector Machine (SVM)</li>
    <li><strong>Tools</strong>: Python, scikit-learn, Matplotlib</li>
    <li><strong>Dataset</strong>: Digits dataset from scikit-learn</li>
    <li><strong>Key Features</strong>:
        <ul>
            <li>Data Preprocessing: Reshaping images into feature vectors and splitting data into training and testing sets.</li>
            <li>Model Training: Training SVM with different kernels (linear, RBF, etc.) and analyzing performance.</li>
            <li>Evaluation: Model accuracy comparison across different kernels, visualization of predictions.</li>
        </ul>
    </li>
</ul>
<p>For more details, refer to the <a href="https://github.com/hellopavi/machine_learning_projects/tree/main/digit_classify_svm">project folder</a>.</p>

<h2 id="installation">Installation</h2>
<p>To run any of these projects locally, you need to have Python installed along with the required libraries. You can install the dependencies using:</p>

<pre><code>pip install pandas numpy scikit-learn matplotlib</code></pre>

<p>Each project folder contains a Jupyter Notebook (<code>.ipynb</code>) file with the code and explanations.</p>

<h2 id="contributing">Contributing</h2>
<p>Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.</p>

