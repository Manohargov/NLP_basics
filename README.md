# NLP_basics
NLP, or Natural Language Processing, is a field of artificial intelligence (AI) that focuses on enabling computers to understand, interpret, generate, and respond to human language in a way that is both meaningful and useful.

## 1. Sentence Tokenization

This is the process of dividing a text into individual sentences. Sentence tokenization is a critical first step in many NLP tasks, as it helps in breaking down text into manageable units for analysis.

## 2. Word Tokenization

Word tokenization splits sentences or text into individual words or tokens. It forms the basis of many NLP applications like frequency analysis, part-of-speech tagging, and parsing.

## 3. RegexpTokenizer

This tokenizer uses regular expressions to define patterns for splitting text into tokens. It allows for customized tokenization strategies beyond basic whitespace or punctuation splitting.

## 4. BlankLine Tokenizer

This tokenizer splits text into segments wherever a blank line occurs. It’s useful when working with texts that use blank lines to separate logical units like paragraphs or sections.

## 5. Frequency Distribution

Frequency distribution refers to the counting and analysis of how often words appear in a given text. It helps in understanding the prominence or repetition of terms within the corpus.

## 6. Stop Words

Stop words are commonly used words (such as “and”, “the”, “is”) that are often removed in NLP preprocessing steps because they usually do not carry significant meaning or contribute to text classification.

## 7. Bigrams, Trigrams, and N-Grams

These are contiguous sequences of words:

Bigram: a pair of consecutive words (e.g., "machine learning").
Trigram: a sequence of three consecutive words.
N-gram: a generalization to n consecutive words.
They help in capturing context and co-occurrence patterns in text.
## 8. Stemming

Stemming is the process of reducing words to their base or root form, usually by stripping suffixes. The resulting stem may not be a real word but is useful for clustering related words (e.g., “running”, “runner” → “run”).

## 9. Lemmatization

Lemmatization is more sophisticated than stemming. It reduces words to their dictionary base form (lemma), using grammatical context. For instance, “better” becomes “good”, and “running” becomes “run”.

## 10. Part-of-Speech (POS) Tagging

POS tagging assigns grammatical labels (noun, verb, adjective, etc.) to each word in a sentence. This helps in understanding the structure and meaning of sentences.

## 11. Named Entity Recognition (NER)

NER identifies and classifies proper nouns in text into predefined categories like person names, locations, organizations, and dates. It is widely used in information extraction.

## 12. spaCy

spaCy is an industrial-strength NLP library in Python known for its fast and efficient tokenization, lemmatization, POS tagging, and NER. It offers pre-trained pipelines for multiple languages.

## 13. Chunking

Also known as shallow parsing, chunking groups together words in a sentence to form meaningful phrases (like noun or verb phrases). It typically operates on top of POS tags.

## 14. Chinking

Chinking is the process of removing specific words from chunks. While chunking defines what to include in a phrase, chinking defines what to exclude, based on patterns.

## 15. Context-Free Grammar (CFG)

CFG is a type of formal grammar used to describe the syntactic structure of sentences in a language. It's used in parsing to generate syntax trees and check grammatical correctness.

## 16. Bag of Words (BoW)

BoW is a simple text representation method that converts text into a vector of word counts, ignoring grammar and word order. It’s used for basic text classification and retrieval tasks.

## 17. Count Vectorizer

CountVectorizer is a BoW implementation that converts a collection of text documents into a matrix of token counts. Each document is represented by the frequency of each word it contains.

## 18. TF-IDF Vectorizer

TF-IDF (Term Frequency-Inverse Document Frequency) assigns weight to words based on their frequency in a document relative to the entire corpus. It helps down-weight common words and highlight rare but important terms.

## 19. Converting Text to Features and Labels

In supervised NLP tasks, text (input) must be converted into numerical features (like using TF-IDF) and labels (like sentiment categories or spam/ham) to train machine learning models.

## 20. Multinomial Naive Bayes

This is a probabilistic classification algorithm commonly used in NLP. It assumes that features (typically word frequencies) are conditionally independent given the class label. It's widely used for tasks like spam detection and document classification.
