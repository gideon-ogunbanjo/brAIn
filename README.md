# brAIn
This AI is designed to assist in spell correction and word suggestion while inputting text. It leverages Neural Language Processing techniques to compare typed words with a vocabulary dictionary and provide helpful corrections and suggestions.

### Features:
- Data Preprocessing: The AI reads a corpus from a file, converts all text to lowercase, and extracts individual words for analysis.

- Vocabulary Creation: It creates a vocabulary set consisting of unique words from the corpus.

- Word Frequency Count: The AI calculates the frequency of each word in the corpus and generates a word-frequency dictionary.

- Word Probability Calculation: Based on the word-frequency dictionary, the AI calculates the probability of each word appearing if randomly selected from the corpus.

- Edit Word Functions: The AI implements various functions to perform word edits, including deleting a letter, switching adjacent letters, replacing letters, and inserting letters.

- Word Correction and Suggestions: By combining the edit operations, the AI suggests corrected words for misspelled or mistyped words. It checks if the edited words exist in the vocabulary and provides the most probable suggestions.

### Usage:
1. Prepare the Corpus: Save the text corpus in a file named sample.txt.

2. Run the Code: Execute the provided Python code to initiate the AI.

3. Enter a Word: When prompted, input a word that needs correction or suggestions.

4. Get Results: The AI will calculate the probabilities, perform word corrections and suggestions, and display the suggested words along with their probabilities.
```
#Example Usage
Enter any word: teh

Word 0: the, Probability 0.567890
Word 1: then, Probability 0.123456
```
In the above example, the user enters the word "teh." The AI suggests the corrected word "the" with a probability of 0.567890 and the word "then" with a probability of 0.123456. Additional suggestions and probabilities are also provided.

### Note
brAIn serves as a basic framework for spell correction and word suggestion. Further enhancements and customizations can be made to improve its accuracy and performance based on specific requirements.

Created by Gideon Ogunbanjo