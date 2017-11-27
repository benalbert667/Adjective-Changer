# Adjective-Changer
Changes adjectives and adverbs in a text to synonyms of themselves

Takes in the text from 'input.txt' and prints out the same text but with all adjectives and adverbs changed to random synonyms of themselves.

First, nltk is used to parse the text sentence by sentence into each individual word and their parts of speech.  Then, synonmys are obtained using PyDictionary for all words given an adjective or adverb flag.  Using one random synonym for each adjective or adverb, the text is reconstructed and printed to the console. 
