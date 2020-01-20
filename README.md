# Forecasting Graduate admission for Master's Application

### CS 634 Data Mining Final Project

The data set has 9 features and 400 observations, in which all the features are numerical. The features are
<ul>
  <li>Serial no</li>
  <li>GRE Score</li>
  <li>TOEFL Score</li>
  <li>University rating</li>
  <li>SOP</li>
  <li>LOR</li>
  <li>CGPA</li>
  <li>Research</li>
  <li>Chance of Admit</li>
</ul>

Though Chance of Admit was a continuous variable, I preprocessed the target variable to create three bins (High, Medium, Low). Once the data is preprocessed, the data is split and normalized. <br>

Once the data is normalized, k-fold cross validation (k = 10) is performed on Decision Tree Classification and Random forest. Then the algorithms are compared, concluding in Random Forest with top 3 features being the best algorithm with cross validated score of 77%.
