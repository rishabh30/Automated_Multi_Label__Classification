### Project Title

# Automated Multi Label Classification (May 2020)


## Problem Statement
Develop a model Multi-categorize items with high precision. NLP is a domain which is so old but still too much to explore. WIth this hackathon we want to identify potential solutions that have the scalability as well as the performance required for a production system. How easily deployable is the solution is a plus.


## Project structure
├── models\
├── main.ipynb\
├── submissions\
├── requirements.txt\
└── License

### Prerequisites

- GPU(s) with 16Gb RAM (e.g. Tesla V100)

```bash
pip install -r requirements.txt
```


### Steps
- Loading data in chunks.
- After loading using googletrans to translate the loaded data into English.
- Compared the similarity of title, link, description, long_description with all level_categories.
- After this added the most similar level_category to the category tree.
- Finally, I converted the output into the CSV file.
- The output file is submitted as Submission, which consists of the prediction of 2000 test cases(id).



### Summary
 
- NLTK
- GoogleTrans
- word_tokenize
