[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/nT4M_vAo)
# Sprint 2 - 90803
### Machine Learning Foundations with Python
#### Spring 2024

---

> Modify here: 

For this Lab, you will need to do the following:

1. Git clone your repo to your local machine (look back at Lab 1 if you have any doubts), using the SSH connection.
2. Open the `Sprint2_S24_TeamName` jupyter notebook and work through it.
3. It is advisable to work on different branches and, in the end, merge your branches to `main`.
4. Periodically go back to the terminal to commit your changes to your Jupyter Notebook. Do not wait until the end; make sure to commit for at least every question in the notebook. Remember that doing a commit involves:
	-  Making changes to your jupyter notebook
	-  Adding changes to your staging area (`git add`)
	-  Committing, with a descriptive message of the task you are committing (`git commit -m "descriptive message"`).
	-  Add a gitignore `git add .gitignore` - for the files you want the commit to ignore. For example, in MacOS you might want to ignore `.DS_Store`. Add this to your gitignore `echo .DS_Store >> .gitignore`. Other files that you might want to include here are `ipynb_checkpoints/*`.
	-  Here are some links if you want to read more on [ipynb checkpoints](https://stackoverflow.com/questions/46421663/what-are-jupyter-notebook-checkpoint-files-for) or how to [gitignore](https://stackoverflow.com/questions/35916658/how-to-git-ignore-ipython-notebook-checkpoints-anywhere-in-repository) them.
5. When you are ready to push back to your GitHub remote repo, make sure to:
	- Have any branches merged into `main`
	- `git push origin main`
	- Have your passphrase at hand
	- After the first push, remember to always `git pull` before working on your local repo (to make sure you're up to date) and then `git push` when you are ready to push changes back to your remote repo.

## Notes on this Sprint - To Modify
- Please follow the instructions provided in the videos (CANVAS)
- Once you are done, please answer the questions below. Make sure you have discussed and come to a consensus when addressing the following questions.

> Modify here: 

**1. List the names of all your teammates:**
Gracie Siu, Sharon John, Sara Clemente

**2. Agree as a team, what branching strategy do you plan to use in your final projects? Justify your choices**
We will each work on our own branches and merge to a main branch

**3.Communication: Outline how the team will communicate — including frequency and methods (e.g., email, WhatsApp, team meetings).  What is the maximum expected response time?**
We will communicate via WhatsApp
Expected response time is same day

**4. Decision-Making: How will decisions be made in this team? How will you stay on track? Do you plan on having meetings or any strategies for working through your final project**
Decisions will be made through consensus
We will stay on track through mid-sprint deadlines and regular check-ins 
We will meet in person (prefer to meet in person) as much as possible for regular project items

**5. As with any team project there is always the possibility of conflict arising, if it does in the future, how will you resolve differences? List at least two strategies**
We will resolve differences through open and honest communication and discussion, over snacks and good coffee!


**6.Commitments: How will you handle different levels of participation and commitment? What process will you follow if someone does not live up to his/her/their responsibilities? (3-5 sentences)**
We will openly discuss with the team member with curiosity - assume an oops not an ouch!


**7.Diversity: How will you accommodate different learning and working styles? Talk about your own styles and schedules for working and come to an agreement (3-6 sentences)**
We all like to meet in the mornings before classes, which works well
Sharon likes to use interview rooms which will work well for meeting locations in Heinz
We all will support each other in this project by ensuring that we are all on the same page of a question or area of the project before moving on to the next phase. 


## Sprint 6


#### Running the Project / Getting Started
- From the Main Branch: 
	- Source files must be pulled from Google Drive. There are two source files:
		- 'Gender_StatsData.csv'
		- 'Share of graduates by field, female (%).csv'
	- To run the original data cleaning, preprocessing, and data scaling, and generate the resulting data set to be used for the models, run file named: “Sprint3_S24_Team13.ipynb
	- To run the models for question 1 run notebook: Question1Sharon.ipynb
	- To run the models for question 2 run notebook:Question2Gracie.ipynb
	- To run the models for question 3 run notebook:Question3Sara.ipynb
Note: all 3 notebooks with models utilize the same dataset. 

#### Disclaimer
The purpose of this project is to explore the multi-dimensional nature of women’s education and mobility. The results presented are solely intended to meet the requirements of a specific assignment in an academic setting. The project was limited to data collected by external sources and we (the authors) did not evaluate the data collection or methodologies used by these sources. We recognize that there may be cultural differences that we did not adequately account for in the limited time that this project was completed. Any conclusions drawn from this project must be taken in the context of the limited scope and potential for bias in data collection.


## Sprint 5 
	The feature engineering and data preparation for the models is in the Sprint 3 notebooks
	The models for question 1 are in a notebook labeled Question1Sharon.ipynb
	The models for question 2 are in a notebook labeled Question2Gracie.ipynb
	The models for questions 3 are in a notebook labeled Question3Sara.ipynb

### Model Evaluation

For Prediction questions (Questions 1 & 2)
Evaluate (and write) how to gain robust performance metrics for your problem. 
	A prediction model is attempting to forecast a future outcome based on historical data. Especially when a problem space is not linear, machine learning techniques may be helpful in achieving a more accurate prediction. When using a model to predict, we are interested in measuring the “difference” or variation between the outcome that actually happens, and the outcome that we predicted. A better model should do a better job at predicting the outcome. In addition, the features that are selected to train the model and their respective influence on the model may provide insight beyond the predictions. We will want to examine the features that are impacting each model to confirm they seem intuitive and logical. 

	In addition, we want to ensure that the model is not overly influenced by the training data and does not suffer from overfitting, which could impact its performance on unseen data. 


What metric/s and techniques you will focus on and why. The why must be related to the context of your questions.
	For our prediction questions, we will examine mean squared error, and r-squared. The mean squared error will measure the variability between the predicted and actual y-values, and the r-squared will provide an estimate of how well the model is predicting the outcome. 

	These metrics will allow us to more confidently predict the anticipated rates of enrollment in questions 1 and 2, and the feature importances in the model may provide insight into the way in which that prediction is influenced (i.e. which features are most significant). 

For Unsupervised questions (Question 3)
How will you use and interpret the results for your own question/s.
	We will plot the cluster assignments from the resulting models to compare metrics of interest by country. For example, STEM graduates vs. Secondary School Enrollment could be plotted by country. The cluster assignments may offer insights into “types” of countries that have similar characteristics that could be influencing STEM major enrollment.  
	
	These results could help to illuminate for stakeholders in this field what factors are influencing enrollment rates, because we know that the relationships between these variables are not linear, and other methods to understand them (such as regression) may not properly account for non-linear relationships. 

Metrics you will use.
	Silhouette scores
	Linkages (for Agglomerative clustering)

### Question 1: What is the relationship between various socio-economic factors and the share of female STEM graduates over time, and can these factors predict future trends in the proportion of women entering STEM fields?
Target variable(s) from data set: ‘Share of STEM Graduates’ 
Task type: prediction

Model 1: Linear Regression
	Parameters to tune: None
	Feature engineering: Data Standardization and Feature Selection
	Metrics: R2 and MSE
Model 2: Ridge
	Parameters to tune: alphas = (-2, 8, 100)
	Feature engineering: N/A (regularized model)
	Metrics: R2 and MSE
Model 3: Random Forest
	Parameters to tune: 'max_depth': [5, 10, 20], 'max_features': [5, 10, 20] ,'min_samples_split': [2, 5, 10]
	Feature engineering: Data Standardization and Feature SelectioN
	Metrics: R2 and MSE
	NEW! Model 4: ElasticNet 
	Parameters to tune: 'alpha': [0.01, 0.1, 1, 10],  
    'l1_ratio': [0.1, 0.5, 0.7, 0.9] type
	Feature engineering: Data Standardization and Feature SelectioN
	Metrics: R2 and MSE
Model Comparison: 
The Random Forest model appears to perform the best on the training data, achieving a high R-squared value and low MSE. However, due to the drop in performance on the test data, it may mean that it suffers from overfitting. However, taking into consideration as this model performs relativly the best as compared to the other models, as a data analyst I would choose RF as my model of choice when addressing this question as it shows the most promise if we took a better look into the data and refinement.

### Question 2: Are women more likely to complete secondary education in some countries than others? In the coming years, what percentage of women overall and by country, do we expect to enroll in secondary education? What factors indicate whether or not a women completes secondary education?
Target variable(s) from data set: 'School enrollment, secondary, female (% gross)' 
Task type: prediction

Model 1: Linear Regression
	Parameters to tune: N/A
	Feature Engineering: Sequential Feature Selection
	Metrics: Mean Squared Error, R-squared
Model 2A: Ridge 
	Parameters to tune: Alphas
	Feature engineering: N/A (regularized model)
	Metrics: Mean Squared Error, R-squared
Model 2B: Lasso
	Parameters to tune:Alphas
	Feature engineering: N/A (regularized model)
	Metrics: Mean Squared Error, R-squared
Model 3: Ensemble - Random Forest Regressor 
	Parameters to tune: max_depth, max_features, min_samples_split
	Feature engineering: Data standardization
	Metrics: Mean Squared Error, R-squared
NEW! Model 4: ElasticNet
	Parameters to tune: Alphas
	Feature engineering: N/A (regularized model)
	Metrics: Mean Squared Error, R-squared
Model Comparison:
	The Random Forest Regressor has a very high r squared for the training data but is a little lower for the r squared for the test data, so there may be concerns of overfitting.
	The ElasticNet model did improve quite a bit with hyperparameter tuning, but even the hypertuned model performs quite a bit worse than most of the other models.
	The ridge model improved a little bit with the hypertuning, but mostly the MSE just decreased after choosing the best alpha.
	The basic linear regression performs pretty well compared to the other models, even compared to the hypertuned models.

### Question 3: Are there "groups" of countries that share characteristics among macroeconomic factors, and education rates among women, and/or women's rights in those countries? For example, do countries with greater rates of education among females and more equal rights among men and women have higher GDP or longer average lifespans?
Target variable(s) from data set: N/A, this is an unsupervised learning question 
Task type: Clustering

Model 1: KMeans Clustering
	Parameters to tune: n_clusters
	Feature engineering: PCA
	Metrics: 
	Distortion score & Calinski-Harabasz to compare k (number of clusters)
	Silhouette score and silhouette plotting to determine n_clusters
Model 2: Hierarchical / Agglomerative Clustering
	Parameters to tune: n_clusters, linkage metric 
	Feature engineering: PCA
	Metrics: 
	Linkage metrics: ‘ward’, ‘average’, ‘complete’, ‘centroid’
Model 3: N/A (unsupervised model)
	Parameters to tune:N/A (unsupervised model)
	Feature engineering: N/A (unsupervised model)
	Metrics:N/A (unsupervised model)
NEW! Model 4: DBSCAN?
	Parameters to tune: eps, min_samples
	Feature engineering: PCA
	Metrics: 
	Silhouette score
Model Comparison: 
	Overall, the agglomerative clustering model seemed to produce the most “useful” results - the clusters appear to be more spread out and easier to interpret when plotting the variables of interest, and the number of clusters (7) may allow more for more interpretation of different variables. 

### Ethical Consideration
Discuss as a team any ethical considerations related to your specific problem. These can be regarding the data, the model itself, and the results to be presented.
	A big concern with a dataset like this is thinking about whether the data and models are biased. With a sensitive issue like women's rights, using the results of these models for policy applications could lead to discrimination. Bias is especially important within the context of secondary schooling because of the fact that women's education is a controversial topic in certain countries. Additionally, women are already a marginalized group, but we need to consider how these models perform for different subsets of women. We must consider whether the model predicts similarly across different demographics, income levels, and ethnicities. If not, is this an issue because of data gaps or because of biases in our model? It's important to also mention the limitations and concerns with the models and their performance when describing the results to women's rights and educational stakeholders. The interpretations and results from a model such as this could have serious affects on policies and the trajectory of women's lives, which is why it's important to consider the previously mentioned ethical concerns for this project.

### Additional Models
Additional Models
This section must include which additional models you plan to use in your projects and how. The how should include a description of which questions will have the specific additional models or if you plan to add an additional question to your project to cover this requirement.

- For question 1, we will incorporate the ElasticNet model as an additional approach to regression analysis. Unlike traditional linear regression, ElasticNet combines the penalties of both Lasso and Ridge regression, making it suitable for datasets with multicollinearity or a large number of features. However, elasticNet did not yeild the best results, with low R-squared values and relatively high MSE. It failed to capture the underlying patterns in the data effectively.

- For question 2, the additional model used will be ElasticNet. We will use this to try a regression that uses a combination of the different types of penalty terms, whereas the ridge model we tried used only one type of penalty term.
- For question 3, the additional model used will be DBSCAN. We chose DBSCAN in hopes that it would create better clusters with our data, which has significant overlap. We tuned the epsilon and min number of samples. We also tested the model with both the scaled data set and with PCA. Lastly, we conducted additional feature engineering by limiting the data set to a single year to draw clearer insights from the clusters.


### References:
https://pandas.pydata.org/docs/reference/api/pandas.melt.html
Lab 2 from EDA
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.pivot_table.html
https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.astype.html
https://genderdata.worldbank.org/resources/?tab=gender-data-portals



## Sprint 3 - 90803
Machine Learning Foundations with Python
Spring 2024
Project Title: Gender Difference Indicators and Share of female STEM graduates
Team Names & Emails: Sara Clemente (saraclem@andrew.cmu.edu), Sharon John (sharonjo@andrew.cmu.edu), Gracie Siu (gsiu@andrew.cmu.edu)
Project Description: Why is this topic relevant? Gender disparities persist in STEM fields worldwide, with women being underrepresented in these areas compared to men. Addressing these disparities is crucial for achieving gender equality and ensuring that all individuals have equal opportunities to pursue careers in high-demand fields.
Who does this topic affect? Where does it happen? When did it happen? This topic affects various stakeholders, including individuals, communities, industries, and economies. For individuals, it impacts career opportunities, earning potential, and professional fulfillment. Communities benefit from diverse perspectives and solutions that arise from gender-inclusive STEM environments. Industries benefit from tapping into a broader talent pool, fostering innovation, and addressing skill shortages. Economies benefit from increased productivity, competitiveness, and economic growth when all segments of the population are fully engaged in STEM fields.
The scope: Gender disparities happen in STEM worldwide, although the extent of these disparities may vary across regions and countries.While some countries have made significant strides in promoting gender diversity in STEM, others continue to face significant challenges. This issue is not limited to a specific geographic location but rather spans across continents and cultures.
Timeline: Gender disparities in STEM have historical roots, stemming from systemic biases, social norms, and cultural expectations. While progress has been made in recent decades to address these disparities, significant gaps persist. Understanding the historical context of gender inequalities in STEM is essential for designing effective interventions and policies to promote diversity and inclusion.
What are your motivations for addressing this topic? As three women in STEM we know the beauty but also challenges in this field. Addressing gender disparities in STEM is not only a matter of social justice but also an economic imperative. By ensuring equal access and opportunities for all individuals in STEM fields, societies can unlock the full potential of their human capital, drive innovation, and build a more equitable and prosperous future for everyone.
Datasets: Gender data: https://genderdata.worldbank.org/ Format: CSV Metadata: The Gender Data Portal is more than just a database of sex-disaggregated data and gender statistics. Data sources include United Nations, UNESCAP, Eurosat, World Economic Forum, WHO, IMF, Institute for Democracy and Electoral Assistance, and more (World Bank).
Variables: Multiple indicators representing gender differences by Country, Year. Indicators span assets, legal rights, education rights and completion, employment, life expectancy, GDP.
Share of female STEM graduates: https://genderdata.worldbank.org/indicators/se-ter-grad-fe-zs/?fieldOfStudy=Science%2C%20Technology%2C%20Engineering%20and%20Mathematics%20%28STEM%29 Format: CSV Metadata: For aggregate data, each economy is classified based on the classification of World Bank Group's fiscal year 2020 (July 1, 2019-June 30, 2020) (Worldbank) Statistical concept and methodology: Percentage of female graduates by field of study in tertiary education is calculated by dividing the number of female graduates in a given field of education from tertiary education by the total number of graduates in the same field, and multiplying by 100. Data on education are collected by the UNESCO Institute for Statistics from official responses to its annual education survey. All the data are mapped to the International Standard Classification of Education (ISCED) to ensure the comparability of education programs at the international level. The current version was formally adopted by UNESCO Member States in 2011. The reference years reflect the school year for which the data are presented. In some countries the school year spans two calendar years (for example, from September 2010 to June 2011); in these cases the reference year refers to the year in which the school year ended (2011 in the example). Source: UNESCO Institute for Statistics (http://uis.unesco.org/). Data as of March 2020. Variables: Share of graduates by field, female (%). Broken down by Country, Year.
Project Questions: Question 1: In the coming years, are women in certain countries more likely to graduate with a STEM major than others? What factor(s) influence women’s access to STEM fields? Can we expect the proportion of women entering STEM fields to grow in the future? If yes, what factors will influence this growth?
Target variable(s) from data set: ‘Share of STEM Graduates’ Task type: prediction
The baseline model coded for Sprint 4 for this question is in the notebook titled "Question1Sharon.ipynb".
Question 2: Are women more likely to complete secondary education in some countries than others? In the coming years, what percentage of women overall and by country, do we expect to enroll in secondary education? What factors indicate whether or not a women completes secondary education?
Target variable(s) from data set: 'School enrollment, secondary, female (% gross)' Task type: prediction
The baseline model coded for Sprint 4 for this question is in the notebook titled "Question2Gracie.ipynb".
Question 3: Are there "groups" of countries that share characteristics among macroeconomic factors, and education rates among women, and/or women's rights in those countries? For example, do countries with greater rates of education among females and more equal rights among men and women have higher GDP or longer average lifespans?
Target variable(s) from data set: N/A, this is an unsupervised learning question Task type: Clustering
How to run the file: The information from Sprint 3 is in one notebook, labeled Sprint 3.
For Sprint 5, we have four separate notebooks:
The feature engineering and data preparation for the models is in the Sprint 3 notebooks
The models for question 1 are in a notebook labeled Question1Sharon.ipynb
The models for question 2 are in a notebook labeled Question2Gracie.ipynb
The models for questions 3 are in a notebook labeled Question3Sara.ipynb
Model Evaluation:
Ethical Considerations:
A big concern with a dataset like this is thinking about whether the data and models are biased. With a sensitive issue like women's rights, using the results of these models for policy applications could lead to discrimination. Bias is especially important within the context of secondary schooling because of the fact that women's education is a controversial topic in certain countries. Additionally, women are already a marginalized group, but we need to consider how these models perform for different subsets of women. We must consider whether the model predicts similarly across different demographics, income levels, and ethnicities. If not, is this an issue because of data gaps or because of biases in our model? It's important to also mention the limitations and concerns with the models and their performance when describing the results to women's rights and educational stakeholders. The interpretations and results from a model such as this could have serious affects on policies and the trajectory of women's lives, which is why it's important to consider the previously mentioned ethical concerns for this project.
Additional Model:
For question 1, the additional model used will be generalized linear regression. We will use this to try out a different type of regression that works well when the distribution is not normal.
For question 2, the additional model used will be ElasticNet. We will use this to try a regression that uses a combination of the different types of penalty terms, whereas the ridge model we tried used only one type of penalty term.
For question 3, the additional model used will be DBSCAN. We will try this different clustering method to see if it clusters better than the other two unsupervised models we have.
References:
https://pandas.pydata.org/docs/reference/api/pandas.melt.html
Lab 2 from EDA
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.pivot_table.html
https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.astype.html
https://genderdata.worldbank.org/resources/?tab=gender-data-portals
Submission Include your Jupyter Notebook/s in the repo Add your dataset to your .gitignore if you are working on it in your local repo, but make sure to provide an exact link for us to download your dataset/s Modify the second half of your README from Sprint 2 to include your project description, questions, etc. Here's a sample: Sprint3_README_Sample-1.md Download Sprint3_README_Sample-1.md Push everything to the same repo you had from Sprint 2 before Thursday, February 29th at 11:59 PM
NOTES:
Gender data: https://genderdata.worldbank.org/
Share of female STEM graduates: https://genderdata.worldbank.org/indicators/se-ter-grad-fe-zs/?fieldOfStudy=Science%2C%20Technology%2C%20Engineering%20and%20Mathematics%20%28STEM%29
change



Notes from TA Meetings
1 linear regression model (e.g.for a baseline)
1 regularized model (e.g.ridge or lasso)
1 ensemble model (e.g.random forest)
Random forest - tune number of trees, number of estimators, max_features (square root or log)
2-3 hyperparameters for each model
potential new models
Support Vector Machines
Neural Networks
ElasticNet - a combination of lasso + ridge
Other clustering techniques (DBSCAN, MiniBatch, Kmeans, Gaussian Mixture)
Generalized Linear Models (GAMs)
XGBoost

Sprint 5 New Sections


Model Evaluation
Question 1: In the coming years, are women in certain countries more likely to graduate with a STEM major than others? What factor(s) influence women’s access to STEM fields? Can we expect the proportion of women entering STEM fields to grow in the future? If yes, what factors will influence this growth?
Evaluate (and write) how to gain robust performance metrics for your problem. 
What metric/s and techniques you will focus on and why. The why must be related to the context of your questions.


Question 2: Are women more likely to complete secondary education in some countries than others? In the coming years, what percentage of women overall and by country, do we expect to enroll in secondary education? What factors indicate whether or not a women completes secondary education?
Evaluate (and write) how to gain robust performance metrics for your problem. 
What metric/s and techniques you will focus on and why. The why must be related to the context of your questions.


Question 3: Are there "groups" of countries that share characteristics among macroeconomic factors, and education rates among women, and/or women's rights in those countries? For example, do countries with greater rates of education among females and more equal rights among men and women have higher GDP or longer average lifespans?
How will you use and interpret the results for your own question/s.
We will plot the cluster assignments from the resulting models to compare metrics of interest by country. For example, STEM graduates vs. Secondary School Enrollment could be plotted by country. The cluster assignments may offer insights into “types” of countries that have similar characteristics that could be influencing STEM major enrollment.  
These results could help to illuminate for stakeholders in this field what factors are influencing enrollment rates, because we know that the relationships between these variables are not linear, and other methods to understand them (such as regression) may not properly account for non-linear relationships. 
Metrics you will use.
Silhouette scores
Linkages (for Agglomerative clustering)




Ethical Consideration
Discuss as a team any ethical considerations related to your specific problem. These can be regarding the data, the model itself, and the results to be presented.


Additional Models
This section must include which additional models you plan to use in your projects and how. The how should include a description of which questions will have the specific additional models or if you plan to add an additional question to your project to cover this requirement.

Question 1:
Question 2: 
Question 3: 


Question 1
In the coming years, are women in certain countries more likely to graduate with a STEM major than others? What factor(s) influence women’s access to STEM fields? Can we expect the proportion of women entering STEM fields to grow in the future? If yes, what factors will influence this growth?
Target variable(s) from data set: ‘Share of STEM Graduates’ 
Task type: prediction
Model 1: Linear Regression
Parameters to tune:
Feature engineering: 
Metrics:
Model 2: Ridge/Lasso
Parameters to tune:
Feature engineering: 
Metrics:
Model 3: Ensemble
Parameters to tune:
Feature engineering: 
Metrics:
NEW! Model 4: Generalized Linear Model
Parameters to tune:
Feature engineering: 
Metrics:
Model Comparison: 
Question 2
Are women more likely to complete secondary education in some countries than others? In the coming years, what percentage of women overall and by country, do we expect to enroll in secondary education? What factors indicate whether or not a women completes secondary education?
Target variable(s) from data set: 'School enrollment, secondary, female (% gross)' 
Task type: prediction
Model 1: Linear Regression
Parameters to tune:
Feature engineering: 
Metrics:
Model 2: Ridge/Lasso
Parameters to tune:
Feature engineering: 
Metrics:
Model 3: Ensemble
Parameters to tune:
Feature engineering: 
Metrics:
NEW! Model 4: ElasticNet
Parameters to tune:
Feature engineering: 
Metrics:
Model Comparison:
Question 3
Are there "groups" of countries that share characteristics among macroeconomic factors, and education rates among women, and/or women's rights in those countries? For example, do countries with greater rates of education among females and more equal rights among men and women have higher GDP or longer average lifespans?
Target variable(s) from data set: N/A, this is an unsupervised learning question 
Task type: Clustering
Model 1: KMeans Clustering
Parameters to tune: n_clusters
Feature engineering: PCA
Metrics: 
Distortion score & Calinski-Harabasz to compare k (number of clusters)
Silhouette score and silhouette plotting to determine n_clusters
Model 2: Hierarchical / Agglomerative Clustering
Parameters to tune: n_clusters, linkage metric 
Feature engineering: PCA
Metrics: 
Linkage metrics: ‘ward’, ‘average’, ‘complete’, ‘centroid’
Model 3: 
Parameters to tune:
Feature engineering: 
Metrics:
NEW! Model 4: DBSCAN?
Parameters to tune: eps, min_samples
Feature engineering: PCA
Metrics: 
Silhouette score
Model Comparison: 












Sprint 2, 3, & 4
Project Title: Gender Difference Indicators and Share of female STEM graduates

Team Names & Emails: Sara Clemente (saraclem@andrew.cmu.edu), Sharon John (sharonjo@andrew.cmu.edu), Gracie Siu (gsiu@andew.cmu.edu)


Project Description: 
Why is this topic relevant?
Gender disparities persist in STEM fields worldwide, with women being underrepresented in these areas compared to men. Addressing these disparities is crucial for achieving gender equality and ensuring that all individuals have equal opportunities to pursue careers in high-demand fields.

Who does this topic affect? Where does it happen? When did it happen?
This topic affects various stakeholders, including individuals, communities, industries, and economies. For individuals, it impacts career opportunities, earning potential, and professional fulfillment. Communities benefit from diverse perspectives and solutions that arise from gender-inclusive STEM environments. Industries benefit from tapping into a broader talent pool, fostering innovation, and addressing skill shortages. Economies benefit from increased productivity, competitiveness, and economic growth when all segments of the population are fully engaged in STEM fields.

The scope: Gender disparities happen in STEM worldwide, although the extent of these disparities may vary across regions and countries.While some countries have made significant strides in promoting gender diversity in STEM, others continue to face significant challenges. This issue is not limited to a specific geographic location but rather spans across continents and cultures.

Timeline:
Gender disparities in STEM have historical roots, stemming from systemic biases, social norms, and cultural expectations. While progress has been made in recent decades to address these disparities, significant gaps persist. Understanding the historical context of gender inequalities in STEM is essential for designing effective interventions and policies to promote diversity and inclusion.


What are your motivations for addressing this topic?
As three women in STEM we know the beauty but also challenges in this field. Addressing gender disparities in STEM is not only a matter of social justice but also an economic imperative. By ensuring equal access and opportunities for all individuals in STEM fields, societies can unlock the full potential of their human capital, drive innovation, and build a more equitable and prosperous future for everyone.

Datasets:
Gender data: https://genderdata.worldbank.org/
Format: CSV
Metadata: 
The Gender Data Portal is more than just a database of sex-disaggregated data and gender statistics. Data sources include United Nations, UNESCAP, Eurosat, World Economic Forum, WHO, IMF, Institute for Democracy and Electoral Assistance, and more (World Bank). 

Variables: Multiple indicators representing gender differences by Country, Year. Indicators span assets, legal rights, education rights and completion, employment, life expectancy, GDP. 

Share of female STEM graduates: https://genderdata.worldbank.org/indicators/se-ter-grad-fe-zs/?fieldOfStudy=Science%2C%20Technology%2C%20Engineering%20and%20Mathematics%20%28STEM%29
Format: CSV
Metadata: 
For aggregate data, each economy is classified based on the classification of World Bank Group's fiscal year 2020 (July 1, 2019-June 30, 2020) (Worldbank)
Statistical concept and methodology: Percentage of female graduates by field of study in tertiary education is calculated by dividing the number of female graduates in a given field of education from tertiary education by the total number of graduates in the same field, and multiplying by 100. Data on education are collected by the UNESCO Institute for Statistics from official responses to its annual education survey. All the data are mapped to the International Standard Classification of Education (ISCED) to ensure the comparability of education programs at the international level. The current version was formally adopted by UNESCO Member States in 2011. The reference years reflect the school year for which the data are presented. In some countries the school year spans two calendar years (for example, from September 2010 to June 2011); in these cases the reference year refers to the year in which the school year ended (2011 in the example). Source: UNESCO Institute for Statistics (http://uis.unesco.org/). Data as of March 2020.
Variables: Share of graduates by field, female (%). Broken down by Country, Year. 

Project Questions:
In the coming years, are women in certain countries more likely to graduate with a STEM major than others? 
Target variable(s) from data set: ‘Share of STEM Graduates’, ‘Country Name’
Task type: prediction
What factor(s) influence women’s access to STEM fields?
Target variable(s) from data set: Feature(s) in prediction model
Task type: prediction
Can we expect the proportion of women entering STEM fields to grow in the future? If yes, what factors will influence this growth?
Target variable(s) from data set: ‘Share of STEM Graduates’, ‘Year’, ‘Country Name’
Task type: prediction

How to run the file: 
<<<<<<< HEAD
All the information for our sprint is in one notebook. Reading the CSV, cleaning the datasets, merging and 3 visualizations
Correlation Matrix
Box plots
Line plot
=======
The information from Sprint 3 is in one notebook, labeled Sprint 3.

For Sprint 5, we have four separate notebooks:
- The feature engineering and data preparation for the models is in the Sprint 3 notebooks
- The models for question 1 are in a notebook labeled Question1Sharon.ipynb
- The models for question 2 are in a notebook labeled Question2Gracie.ipynb
- The models for questions 3 are in a notebook labeled Question3Sara.ipynb


Model Evaluation:

Ethical Considerations:

A big concern with a dataset like this is thinking about whether the data and models are biased. With a sensitive issue like women's rights, using the results of these models for policy applications could lead to discrimination. Bias is especially important within the context of secondary schooling because of the fact that women's education is a controversial topic in certain countries. Additionally, women are already a marginalized group, but we need to consider how these models perform for different subsets of women. We must consider whether the model predicts similarly across different demographics, income levels, and ethnicities. If not, is this an issue because of data gaps or because of biases in our model? It's important to also mention the limitations and concerns with the models and their performance when describing the results to women's rights and educational stakeholders. The interpretations and results from a model such as this could have serious affects on policies and the trajectory of women's lives, which is why it's important to consider the previously mentioned ethical concerns for this project.

Additional Model:

- For question 1, the additional model used will be generalized linear regression. We will use this to try out a different type of regression that works well when the distribution is not normal.
- For question 2, the additional model used will be ElasticNet. We will use this to try a regression that uses a combination of the different types of penalty terms, whereas the ridge model we tried used only one type of penalty term.
- For question 3, the additional model used will be DBSCAN. We will try this different clustering method to see if it clusters better than the other two unsupervised models we have.

<<<<<<< HEAD
>>>>>>> 4e7a8f3436ef7a502c19350a4525e01a10ddd3b6
=======
>>>>>>> 4e7a8f3436ef7a502c19350a4525e01a10ddd3b6

References:
- https://pandas.pydata.org/docs/reference/api/pandas.melt.html
- Lab 2 from EDA
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.pivot_table.html
- https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.astype.html
- https://genderdata.worldbank.org/resources/?tab=gender-data-portals

Gender data:
https://genderdata.worldbank.org/

Share of female STEM graduates:
https://genderdata.worldbank.org/indicators/se-ter-grad-fe-zs/?fieldOfStudy=Science%2C%20Technology%2C%20Engineering%20and%20Mathematics%20%28STEM%29
