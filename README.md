## Project Overview
• Created a machine learning model that detects/classifies a SMS into SPAM or HAM (normal) based on the textual data using Natural Language Processing.<br/>
• Engineered features like word_count, contains_currency_symbol, and contains_number from the text SMS.

## How will this project help?
• This project **helps in filtering/cleaning the SMS from the phone.**


## Exploratory Data Analysis (EDA)
• Exploring NaN values in dataset<br/>
• Plotted countplot for SMS labels Spam vs. Ham

## Feature Engineering
• Handling imbalanced dataset using Oversampling<br/>
• **Creating new features** from existing features e.g. **word_count, contains_currency_symbol, contains_numbers**, etc.<br/>


## Data Cleaning


## Model Building and Evaluation
**Metric: F1-Score**<br/>
• Multinomial Naive Bayes: 0.943<br/>
• Decision Tree: 0.98<br/>
• Random Forest: 0.994<br/>
• Voting (Decision Tree + Multinomial Naive Bayes): 0.98<br/>



