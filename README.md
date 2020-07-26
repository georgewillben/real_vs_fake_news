# Classifying News Aricles As Real Or Fake
## By George Bennett
<br>
In this project I recieved a data set containing thousands of news articles, some fake, some real. I used tf-idf vectorization along with traditional machine learning algorithms to classify the articles. At the end I had a mearure of 99% precision and 99% accuracy in classifying the test set. Along the way I gained insights in how to tell if an article is real or fake.
<br>
## Tools Used
* Pandas
* Matplotlib
* Seaborn
* Scipy
* Spacy
* Scikit-learn
* XGBoost

#### In Scikit-learn
* TfidfVectorizer
* GridSearchCV
* LogisticRegression
* DecisionTreeClassifier
* RandomForestClassifier
* classification_report
<br>
# How to navigate this repo
Here is a list of files in this repo. They are ordered in the order I created them and they tell a story of the entire process.
* business_understanding.ipynb
* Data Cleaning and Preprocessing.ipynb
* Exploratory Data Analysis.ipynb
* Random Forest Modeling.ipynb
* XGBoost.ipynb
* Random Forest Modeling.ipynb
* Decision Tree Modeling.ipynb
* Logistic Regression Modeling.ipynb
* Final Evaluation.ipynb
* Executive_Summary.pdf

<br>
# The Process
## Stage 1: Cleaning the data
In this stage I inspected the data and noticed differences in the two sets of articles that could be dead give-aways. Some things such as twitter handles and publisher information had to be removed. Also there were some formating differences such as an added space at the beginning of headlines for fake news.
