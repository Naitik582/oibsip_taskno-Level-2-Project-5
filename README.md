<h1>Autocomplete and Autocorrect Data Analytics</h1>

**Project Overview:**

• This project explores the efficiency and accuracy of autocomplete and autocorrect algorithms using data analytics and NLP techniques. The aim is to improve user experience in text prediction and correction through model implementation and performance comparison.


**Dataset Used:**

• File Name: creditcard.csv

• Columns: Time, V1–V28, Amount, Class (Note: Only text-like data used for NLP logic simulation)



**Key Objectives:**

1. Collect and understand structured dataset


2. Preprocess data (tokenization, vocabulary extraction)


3. Build a simple autocomplete system


4. Implement autocorrect using:

   Edit Distance

   Jaccard Similarity


5. Compare models for accuracy



6. Visualize results


7. Ensure code simplicity and readability




**Technologies Used:**

• Language: Python

• Libraries:

• pandas – Data handling

• re – Text cleaning

• matplotlib – Data visualization

• nltk – NLP tokenization

• string, collections, itertools – Utility functions



**Project Structure:**

• Data Loading & Exploration

• Text Preprocessing

• Autocomplete Function

• Autocorrect Functions (Edit Distance & Jaccard)

• Accuracy Comparison

• Visualization (bar chart)



**How to Run:**

1. Upload creditcard.csv in Google Colab


2. Run each cell step by step


3. Test custom input for suggestions/corrections


4. View performance chart at the end



**Results:**

• Both models provide reasonable predictions

• Edit Distance performs better in certain cases

• Jaccard is faster but less accurate for spelling errors



**Future Scope:**

• Use real text datasets (tweets, comments)

• Apply ML-based models (e.g., BERT, LSTM)

• Add feedback collection and UI demo
