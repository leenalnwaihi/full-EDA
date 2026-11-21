# full-EDA
# Week 4 - Text Data Analysis and Cleaning

## Project Overview
This project focuses on analyzing and cleaning text data using Python and Natural Language Processing (NLP) techniques.

The goal is to understand the dataset, identify text quality issues, and prepare the text for further analysis.

## Dataset
- File name: `df_file.csv`
- Total documents: 2,225
- Columns: `Text` and `Label`
- Language: English

## Tools and Libraries
The following tools and libraries were used:
- Python
- Pandas
- NumPy
- Matplotlib and Seaborn
- Regular Expressions (Regex)
- spaCy
- langdetect

## Work Performed

### 1. Dataset Analysis
- Loaded and explored the dataset.
- Checked dataset size, columns, and data types.
- Analyzed label distribution.
- Examined text length and word count.

### 2. Data Quality Analysis
- Checked for duplicate records and duplicate texts.
- Checked for empty texts and extra spaces.
- Identified URLs, HTML tags, numbers, and special characters.

### 3. Language Detection
- Used `langdetect` to identify the language of each document.
- All 2,225 documents were detected as English.

### 4. Text Processing
Used spaCy to perform:
- Tokenization
- Stop Words Removal
- Lemmatization

### 5. Text Cleaning
Created cleaning functions using Regular Expressions (Regex) to:
- Remove URLs.
- Remove HTML tags.
- Remove email addresses.
- Normalize extra spaces.
- Remove punctuation.
- Convert text to lowercase.
- Remove stop words while preserving important negation words.
- Apply lemmatization.

### 6. Testing
- Tested the cleaning function using different text examples.
- Checked how the function handles empty and invalid inputs.
- Used basic validation tests to check the cleaning results.
- Compared original text with cleaned text.

## Main Output
A new column called `clean_text` was added to the dataset. It contains the cleaned version of the original text.

## Conclusion
This project helped me understand the main steps of text analysis and cleaning. It also showed how NLP tools can be used to prepare raw text data for future tasks.

Text cleaning should be performed carefully because removing important words or information can change the original meaning.
