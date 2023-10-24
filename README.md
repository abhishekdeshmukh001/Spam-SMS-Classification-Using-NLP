## Title: Spam SMS Classification Using NLP

### A. Project Overview:
This project focused on classifying SMS messages as either "Spam" or "Ham" (non-spam). The dataset includes two columns: 'label' and 'message.'

### B. Dataset Description: 
The dataset contained 2 columns, namely 'Label' and 'Message'.
We will be using the following dataset:

      Spam SMS Collection
-----

## -Tasks Performed:

### 1. Handling Imbalanced Data:
* Addressed the dataset's imbalance by oversampling the minority class (Spam) using code to create additional samples of Spam messages.

### 2. Feature Engineering:
* Created a new feature, 'word_count,' to capture the word count in each message.
* Visualized word count distribution using subplots 'Distplot' for Ham and Spam messages.
* Created a 'contains_currency_symbol' feature and plotted a Countplot to reveal the prevalence of currency symbols in Spam messages.
* Created a 'contains_number' feature and plotted a Countplot with 'label' as hue to highlight the presence of numbers in messages.

### 3. Data Cleaning:
Conducted data cleaning steps, including:
 * Removing special characters and numbers using regular expressions.
 * Converting all messages to lowercase.
 * Tokenizing messages into words.
 * Removing stop words.
 * Lemmatizing words using the WordNetLemmatizer.
 * Joining the lemmatized words to form a corpus of messages.
      

### 4. Model Implementation:
* Implemented multiple machine learning models, including Multinomial Naive Bayes, Random Forest, and Decision Tree.
* Generated classification reports for all models using scoring='f1'.
* Built and visualized confusion matrices for all models to assess model performance.

### 5. Model Selection:
* Selected the **Random Forest** model for prediction as it exhibited the highest accuracy of **99.40%** in classifying Spam and Ham messages.

### 6. Sample Output:

***1. sample_message*** = 'IMPORTANT - You could be entitled up to £3,160 in compensation from mis-sold PPI on a credit card or loan. Please reply PPI for info or STOP to opt out.'

***Output***: Gotcha! This is a SPAM message.
###

***2. sample_message*** = 'Sam, your rent payment for Jan 19 has been received. $1,300 will be drafted from your Wells Fargo Account ******0000 within 24-48 business hours. Thank you!'

***Output***: This is a HAM (normal) message.


## 🔗 Link
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhishek-sachin-deshmukh/)


## Authors

- [@abhishekdeshmukh001](https://github.com/abhishekdeshmukh001)
