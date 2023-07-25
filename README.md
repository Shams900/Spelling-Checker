# Spelling-Checker
This is a Python class for checking the spelling of words using a valid words. 
The SpellChecker class has the following methods:
1. __init__(self, dictionary)
This method initializes the SpellChecker object with a dictionary of valid words. The dictionary should be provided as a list of strings, where each string represents a valid word. The method stores the dictionary in a hash table for efficient lookup.
2. nearest_4_words(self, word)
This method takes a word as input and returns the two words that occur immediately before and after the input word in the dictionary, if they exist. If the input word is in the dictionary, an empty list is returned.
3. add_word(self, word)
This method adds a new word to the dictionary. The word should be provided as a string.

Usage:
To use the SpellChecker class, you can create a new instance of the class and pass your valid words. 
