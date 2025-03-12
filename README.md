# Extractive Summarization for Financial Texts

This project focuses on **summarizing financial news and reports** using extractive summarization techniques. The goal is to identify and extract the most important sentences from financial texts while maintaining key information.

## Author

Eren Akel

## Project Overview

- **Objective**: Automatically summarize financial documents to enhance readability and extract critical insights.
- **Approach**:
  - **Text Preprocessing**: Tokenization, stopword removal, and sentence segmentation.
  - **Scoring Sentences**: Using statistical and linguistic features to rank sentence importance.
  - **Summary Extraction**: Selecting the most relevant sentences based on computed scores.

## How to Run?

1. Install the required dependencies:
   ```bash
   pip install nltk numpy
   ```
2. Download necessary NLP resources:
   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')
   ```
3. Run the notebook and input a financial document for summarization.

## Technologies Used

- **Python (NLTK, NumPy, Regular Expressions)**
- **Natural Language Processing (Text Tokenization, Stopword Removal, Sentence Ranking)**

## License  
This project is created and maintained by **Eren Akel**. Feel free to use and modify for educational purposes.
