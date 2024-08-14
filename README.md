# Data-Extraction Assigment:
This repository contains the code for the Data Extraction and sentiment analysis assignment given by x company, which involves extracting text from articles, performing text cleaning, sentiment analysis, and readability metrics computation. The output is saved in an Excel file.

## This Assignment is designed to:
- Extract text from article files based on URL IDs.
- Clean the extracted text by removing stop words and non-alphanumeric characters.
- Perform sentiment analysis to calculate positive, negative, polarity, and subjectivity scores.
- Compute various readability metrics such as average sentence length, fog index, complex word count, etc.
- Save the results in an Excel file.

## Input Files
- **Input.xlsx:** Contains the URL IDs and URLs for the articles to be analyzed.
- **StopWords_Names.txt, StopWords_Geographic.txt, StopWords_GenericLong.txt:** Files containing stop words to be excluded from analysis.
- **positive-words.txt:** List of words considered positive.
- **negative-words.txt:** List of words considered negative.
- Article text files named according to the URL ID (e.g., 123.txt).

## License
This project is licensed under the MIT License - see the LICENSE file for details.
