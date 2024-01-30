
# Data Extraction and Analysis 

## Objective
The primary goal of this project is to extract textual data from provided URLs, perform text analysis, and compute various relevant variables.

## Tools and Libraries
- Pandas: Used for reading the input Excel file (`input.xlsx`) containing URLs.
- BeautifulSoup and Requests: Employed for web scraping and extracting article text from each URL while ensuring exclusion of headers, footers, and irrelevant content.
- NLTK (Natural Language Toolkit): Utilized for text analysis, including tokenization, stop-word removal, and computation of various text variables.

## Implementation Steps

### 1. Data Extraction
- The Pandas library was employed to read the input Excel file (`input.xlsx`) containing URLs.
- BeautifulSoup and Requests were used to extract article text from each URL.
- Ensured exclusion of headers, footers, and irrelevant content during extraction.

### 2. Text Analysis
- NLTK was used for tokenization and stop-word removal.
- Multiple stop-word files and a Master Dictionary for positive and negative words were employed.
- Calculated various variables, including positive score, negative score, polarity score, subjectivity score, average sentence length, percentage of complex words, Fog Index, average number of words per sentence, complex word count, word count, syllables per word, personal pronouns, and average word length.

### 3. Output
- Stored the extracted article text in individual text files with filenames as URL_ID.
- Created a new DataFrame to store the calculated variables for each URL.
- Saved the results in a CSV file (`Output Data Structure.csv`) with the specified structure.

## Note
The implementation was done in a Jupyter Notebook, and all files are available in a single directory to prevent conflicts.
---
