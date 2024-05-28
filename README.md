# Text Processing and Spam Classification

This repository contains various notebooks and scripts for text processing, vectorization techniques, and spam classification using machine learning. The included files demonstrate different methods for handling and cleaning text data, vectorizing text, and building classification models, with a focus on managing imbalanced datasets.

## Files and Descriptions

1. **Vectorization_techniques.ipynb**
   - **Description:** Demonstrates various vectorization techniques for text data.
   - **Sections:**
     - Count Vectorization
     - N-gram Vectorization
     - TF-IDF Vectorization
     - Word2Vec Vectorization

2. **All_text_cleaning_techniques.ipynb**
   - **Description:** Covers multiple text cleaning and preprocessing techniques.
   - **Sections:**
     - To Lower Case
     - Removing HTML Tags
     - Removing URLs
     - Removing Numbers
     - Converting Numbers to Words
     - Spelling Correction
     - Converting Accented Chars to ASCII Chars
     - Expanding Contractions
     - Stemming
     - Lemmatizing
     - Emoji Removal
     - Emoticons Removal
     - Removing Punctuations or Special Chars
     - Removing Stopwords
     - Removing Frequent Words
     - Removing Rare Words
     - Removing Single Chars
     - Removing Extra White Spaces

3. **emo_unicode.py**
   - **Description:** A script containing mappings of emojis and emoticons to their Unicode representations or descriptive text.
   - **Usage:** Standardizes or normalizes emojis and emoticons in text data.

4. **SMSSpamCollection**
   - **Description:** Dataset containing SMS messages labeled as "ham" (not spam) or "spam".
   - **Format:** Tab-separated values with two columns: `Label` and `Message`.

5. **spam_classifier.ipynb**
   - **Description:** Notebook for building a spam classification model.
   - **Sections:**
     - Importing Necessary Libraries
     - Loading Data
     - Feature Engineering
     - Text Cleaning
     - Vectorization
     - Splitting Data
     - Machine Learning Model (using Count Vectorized Matrix, N-gram Vectorized Matrix, TF-IDF Vectorized Matrix)
     - Conclusion (achieving around 93% accuracy with N-gram Document Matrix)

6. **spam_handling_imbalanced_data.ipynb**
   - **Description:** Notebook focused on handling imbalanced data in spam classification.
   - **Sections:**
     - With Augmentation
     - RandomOverSampler

