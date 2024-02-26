# Author Identification with NLTK

This project focuses on identifying the author of a given book using various techniques implemented with the Natural Language Toolkit (NLTK) in Python. The identification is based on several factors including Jaccard's probability, vocabulary test, word length test, and non-indexed word frequency.
The project is based on project from book: Real-World Python: A Hacker's Guide to Solving Problems with Code

## Installation

1. Clone the repository:

    ```
    git clone https://github.com/kamlocicho/author-identification.git
    ```

2. Navigate into the project directory:

    ```
    cd author-identification
    ```

3. Open the Jupyter notebook `find_author.ipynb` to access and run the code.

## Usage

1. Ensure you have the book text files you want to analyze placed in the `data` directory.

2. Open the Jupyter notebook `find_author.ipynb`.

3. Run the cells in the notebook sequentially to execute the code and follow the instructions provided within the notebook.

4. The notebook will guide you through the process of identifying the author of the provided book using various NLTK techniques.

## Methodology

### Jaccard's Probability
Jaccard's probability is calculated by comparing the sets of unique words used by different authors. This method calculates the similarity between the word usage patterns of different authors.

### Vocabulary Test
The vocabulary test measures the diversity of vocabulary used by different authors. It compares the number of unique words used by each author to determine the authorship.

### Word Length Test
This test analyzes the average word length used by different authors. It compares the average word length in characters to identify patterns unique to specific authors.

### Non-indexed Word Frequency
Non-indexed word frequency examines the occurrence of less common words (excluding stop words and highly frequent words) to identify distinctive patterns in each author's writing style.
