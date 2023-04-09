# Text-Summarize-Spacy
Summarize any text article using Spacy and nlargest elements

Here, We create a Summarizer that can summarize a given text using Spacy and nlargest function of heap.

First we load the english corpus using Spacy, using 'en_core_web_sm'. Then we use our created class functions to help summarize the data.

WordFrequencyCalculator calculates the frequency of words that are not puntuations and stop_words in the document.

WordFreqNormalizer normalizes the frequency of all words by dividing it by the max frequency.

CalculateSentenceScore calculates the sentence score based on normalized word frequencies calculated before.

Finally, SummarizeText summarizes the text by using the heap nlargest function which returns the n-largest elements of text based on calculated sentence score.


**Dependencies Required**
''''
1. Pandas
2. Numpy
3. Spacy
''''
