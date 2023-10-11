# Sentiment_Analysis_using_NLP

# Text Analysis Using Natural Language Processing (NLP)

This project focuses on performing text analysis using Natural Language Processing (NLP) techniques. The process involves data collection through web scraping, followed by comprehensive data analysis including sentiment analysis, readability assessment, and various metrics for text evaluation.

## Data Collection

The project started with obtaining a list of 114 URLs along with corresponding URL IDs. Web scraping was performed using the Beautiful Soup library to extract articles from the provided URLs. The retrieved text from each URL was saved into .txt files, named according to their corresponding URL ID & saved into scraped articles.zip.

### Challenges Encountered

During the data collection phase, two URLs out of the provided 114 could not be located, resulting in data retrieval from 112 URLs.

## Data Analysis

The data analysis phase involves several steps to gain insights from the collected text.

1. **Reading Scraped Text Files**
   Text files obtained from web scraping were read, initializing the data analysis.

2. **Stop Words Extraction**
   Stopwords were extracted from designated files and compiled into a unified stopwords list.

3. **Tokenizing Text into Words and Sentences**
   NLTK library was used to tokenize the text into individual words and sentences, preparing it for analysis.

4. **Removing Extracted Stopwords from Tokenized Words**
   Stopwords were removed from the tokenized words to obtain cleaned data for further analysis.

5. **Extraction of Positive and Negative Words**
   Positive and negative words were extracted from a master directory.

6. **Calculating Positive and Negative Scores**
   Positive and negative scores were computed using the extracted words, providing insights into text sentiment.

7. **Calculation of Polarity Score**
   Polarity score was calculated to represent the sentiment expressed within the text.

8. **Word Count (Number of Cleaned Words in Text)**
   Total count of cleaned words was calculated, providing an understanding of the text's size.

9. **Calculating Subjectivity Score**
   Subjectivity score was computed, indicating whether the text leans towards being objective or subjective.

10. **Calculating Average Number of Words per Sentence (Average Sentence Length)**
    Average sentence length was calculated to understand the text's structure.

11. **Syllable Count per Words**
    Syllable counts for individual words were determined, aiding in analyzing word complexity.

12. **Complex Word Count and Percentage of Complex Words**
    Count and percentage of complex words (words with more than two syllables) were computed.

13. **Analysis of Readability**
    Readability analysis was performed using the Fog Index formula, gauging the text's ease of comprehension.

14. **Personal Pronoun Count**
    The count of personal pronouns within the text was assessed.

15. **Average Word Length**
    Average word length was calculated to understand the text's lexical characteristics.

## Data Export

The resulting analysis parameters were exported to an Excel file named "OUTPUT FINAL DATA.xlsx" after being compiled into a dataframe.
