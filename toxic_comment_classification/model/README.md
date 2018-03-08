# Notebook Description
The ipython notebooks are run on Google Colaboratory instead of Kaggle kernel, becuase my model need a larger training time in the range of 3-4 hours, and extremely fast computation using. Google Colaboratory fortunately now provides gpu backend.

# File Descrition
1. clean_text_data.ipynb - this notebook cleans the raw text data in the train and test using regular expression and nltk library, and saves the cleaned data in google drive
2. Word2VecGenerator.ipynb - this notebook generates word2vec model using gensim library and save the model.
3. model - creates a multilayered lstm model with gpu computation