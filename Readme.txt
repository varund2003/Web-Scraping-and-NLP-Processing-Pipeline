Data Extraction:

I Used pandas to read the input Excel file (input.xlsx) containing URLs.
Employed BeautifulSoup and requests to extract the article text from each URL while ensuring the extraction excludes headers, footers, etc.


Analysis:

Used NLTK for tokenization and stop-word removal.
Employed multiple stop-word files and a Master Dictionary for positive and negative words.
Calculated various variables, such as positive score, negative score, polarity score, subjectivity score, average sentence length, percentage of complex words, Fog Index, average number of words per sentence, complex word count, word count, syllables per word, personal pronouns, and average word length.

Output:

Stored the extracted article text in individual text files with the filename as the URL_ID.
Created a new DataFrame to store the calculated variables for each URL.
Saved the results in a CSV file (Output Data Structure.csv) with the specified structure.


Note:
I did it in jupter notebook and made all files avaiable in single directory itself to prevent futher conflits