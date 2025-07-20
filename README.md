# Web Scraping and NLP Project – Web Mining and Applied NLP (44-620)

## Author
**Kersha Broussard**  
📍 [GitHub Repo](https://github.com/kersha0530/broussard-web-scraping)

## Overview
This project uses Python to:
- Scrape archived article HTML from the Wayback Machine
- Parse the content using BeautifulSoup
- Analyze the article text with spaCy
- Visualize token and lemma-based sentence relevance with Matplotlib

## Technologies Used
- Python 3.11
- `beautifulsoup4`
- `html5lib`
- `requests`
- `spacy`
- `spacytextblob`
- `matplotlib`
- `pickle`

## Tasks Completed
1. Scraped and saved article HTML.
2. Parsed HTML and extracted plain text.
3. Identified 5 most frequent tokens.
4. Identified 5 most frequent lemmas.
5. Defined and tested scoring functions for tokens and lemmas.
6. Visualized token score distribution.
7. Visualized lemma score distribution.
8. Reflected on how to filter for nouns only.

## Sample Results
- Common Tokens: `['the', 'laser', 'of', 'a', 'headlight']`
- Common Lemmas: `['laser', 'headlight', 'use', 'beam', 'light']`
- Histogram: Sentence relevance scores ranged mostly between **0.05 to 0.15**

## Key Concepts
- **BeautifulSoup**: HTML parser to clean and structure web data
- **spaCy**: Natural language processing library
- **Token**: Smallest unit in text (e.g. words, punctuation)
- **Lemma**: Root form of a word (e.g. "running" → "run")
- **Stop Words**: Common words filtered out in NLP (e.g. "the", "is")
- **Whitespace**: Empty characters that can be ignored in analysis

## Setup Instructions
1. Clone the repo
2. Create and activate a virtual environment
3. Install dependencies using:
    ```
    pip install -r requirements.txt
    ```
4. Launch JupyterLab and run `web-scraping.ipynb`

---

## License
This project is for educational use in Web Mining and Applied NLP (44-620).
# Web Scraping and NLP with Requests, BeautifulSoup, and spaCy

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Article text is correct: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Correct scores for first sentence printed: 2 pts (1 / function)
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Histogram shown with appropriate labelling: 1 pt
* (Question 8) Thoughtful answer provided: 1 pt
