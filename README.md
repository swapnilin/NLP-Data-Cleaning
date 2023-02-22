# NLP-Data-Cleaning

# NLP-Data-Cleaning

In this notebook I will demonstrate how to pre-process and clean text data for Natural Lanuage Processing applications and how to perform Sentiment Analysis on the data.

Pre-processing and data cleaning are crucial steps in any NLP (Natural Language Processing) project. These steps help to ensure that the data used in the project is of high quality, and ready to be used for further analysis and modeling. The following are the common pre-processing and data cleaning steps in an NLP project:

**1. Data collection:** The first step is to collect the data that will be used in the project. This can be done from various sources such as text files, web pages, databases, etc.


**2. Data cleaning:** Remove any irrelevant or redundant information from the data such as special characters, punctuation marks, numbers, etc. This step also involves correcting any spelling mistakes or typos in the data ('recieve' > 'receive', 'brocoli' > 'broccoli').


**3. Text normalization:** Convert all the text data into a uniform format. This involves converting all the text to lowercase or uppercase, converting slang words or ackronyms ( e.g. lol, gn), expanding contractions (can't to can not), removing stop words (a, the, and, but), stemming or lemmatizing the words to reduce words to their base or root form.


**4. Stemming:** Stemming is the process of reducing words to their base form by removing suffixes. e.g. the root word in 'writing' and 'written' is 'write'. You get rid of 'ing', 'ed' ,'en'. Stemming algorithms are fast and efficient, but they can sometimes produce non-words or words with a different meaning than the original word.


**5. Lemmatization:** Lemmatization, on the other hand, is the process of reducing words to their base form using a morphological analysis of words. For e.g. the word 'better'. If we use a stemming algorithm to reduce this word to its base form, it will likely produce 'bett' as the stem. However, this stem is not a meaningful word and does not accurately represent the original word. Lemmatization on the other hand, will reduce the word to its base form or lemma of the word "better" would be "good".

The choice between stemming and lemmatization will depend on the specific requirements of the NLP project and the trade-off between speed and accuracy.


**6. Tokenization:** Tokenization is the process of splitting the text data into smaller chunks or tokens, such as words, phrases, or sentences. This step helps in preparing the text data for further analysis and modeling.


**7. Text vectorization:** Text vectorization is the process of transforming data into a numerical format that can be used for analysis and modeling. This involves converting the text data into numerical vectors using techniques such as bag of words, TF-IDF, or word embeddings.

