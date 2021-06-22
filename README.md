# Summarization
# Extractive Summarization**
**Approach 01:**
we can perform extractive summarization by using run.py

Command: python run.py {story_file_name}

Example: python run.py msft.story

**Approach 02:**
We can perform extractive summarization by using run_nltk.py 
Here it's using NLTK and pagerank algorithm
But the drawback is it only works on small files. we can improve it by reducing the length of the vocabulary (by removing the stopwords etc.,) or using any other technique like reducing the less frequent words, or using TF-IDF.

Command: python run_nltk.py {story_file_name}

Example: python run.py msft.story

# Abstractive Summarization
pre_processing.py --- contains the code for preprocessing the dataset




