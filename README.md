# Semantic-Search

A search engine that gives results using the semantics of the input.

## Overview
This project implements a semantic search engine that understands the meaning behind a query rather than just matching keywords. It ranks results by similarity score, returning the most contextually relevant matches.

## How It Works
1. Input a search query
2. The model encodes the query into a vector embedding
3. Similarity scores are computed against a dataset of texts
4. The top 10 most semantically similar results are returned

## Example Output
Result no. 1 (Similarity: 0.5113)
Text: Poachers Putting Endangered Rhinos at Risk...
Result no. 2 (Similarity: 0.3007)
Text: IT alligator tales I grew up in New York...

## Technologies Used
- Python
- Sentence Transformers
- NumPy
- Google Colab

## Usage
1. Clone the repository
  git clone https://github.com/Djax05/Semantic-Search.git
2. Open `Semantic Search.ipynb` in Google Colab
3. Run all cells
4. Enter your search query when prompted

## Author
Makinde John
