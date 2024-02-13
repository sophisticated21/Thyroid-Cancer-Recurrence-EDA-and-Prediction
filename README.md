# Thyroid-Cancer-Recurrence-EDA-and-Prediction
The aim of this initiative was to forecast the likelihood of thyroid recurrence, utilizing a meticulously assembled dataset designed for this specific goal. The initial phase concentrated on data cleansing—an essential process to eliminate any inconsistencies or incomplete entries.

Stratification was a key aspect of our approach, especially when splitting the data. Using the stratify parameter ensured that our train and test sets reflected the overall distribution of the target variable, crucial for maintaining accuracy in predictive models.

In this analysis, significant variables, such as age, were grouped to illuminate their impact on thyroid recurrence, acknowledging age's pivotal role in health assessments. A detailed evaluation of categorical variables was also conducted to uncover their relationships with the risk of recurrence.

For visual representation, I used bar graphs to illustrate the variables' distribution, ensuring that critical responses were distinctly marked for straightforward recognition.

The data underwent One-Hot Encoding and normalization in the preprocessing stage to ready it for modeling. Among the assessed models, including Logistic Regression and RandomForestClassifier, Logistic Regression was identified as the most proficient in forecasting thyroid recurrence risk.

This model excelled in both the training and validation phases, particularly in accurately classifying cases of thyroid recurrence with notable precision and recall metrics.

In-depth analysis through classification reports and confusion matrices for both training and validation datasets allowed for a precise evaluation of the model's performance across different scenarios. Exploring the importance of features further shed light on the key predictors of thyroid recurrence risk, enhancing our understanding and predictive power in this domain.
