AIM:
To study Natural Language Processing (NLP) techniques such as tokenization, stopword removal, stemming, lemmatization, POS tagging, and word frequency analysis using Python.

THEORY :
nltk.download(): Downloads required NLP datasets like tokenizers, stopwords, and lexical resources.

word_tokenize(): Splits text into individual words (tokens).

sent_tokenize(): Splits text into sentences.

stopwords.words(): Provides a list of common words (like “is”, “the”) to remove from text.

set(): Converts list into a set for faster lookup during filtering.

List comprehension: Used to filter words by removing stopwords efficiently.

PorterStemmer(): Reduces words to their root form by removing suffixes.

stem(): Returns the stemmed (root) version of a word.

WordNetLemmatizer(): Converts words into their meaningful base (dictionary) form.

lemmatize(): Returns the correct base form of a word using vocabulary knowledge.

pos_tag(): Assigns grammatical tags (noun, verb, adjective, etc.) to each word.

FreqDist(): Calculates frequency distribution of words in a text.

most_common(): Returns most frequent words along with their counts.

POS Tagging: Identifies grammatical roles like noun (NN), verb (VB), adjective (JJ), etc.

Text preprocessing: Includes tokenization, stopword removal, stemming, and lemmatization for cleaning text.

CONCLUSION :
In this experiment, various NLP techniques were applied to process and analyze text data. We learned how to tokenize text, remove stopwords, and reduce words using stemming and lemmatization. POS tagging helped identify grammatical roles, and frequency distribution helped analyze word usage. These techniques are essential for text analysis and natural language understanding.
