# NLP Homework Repository

  This repository contains NLP course homework assignments.
  
## Homework 1 – Text Preprocessing (Basic Python)

Objective: Learn basic text preprocessing using only built-in Python functions.

  ***Steps:***

1. Tokenization – Split the text into words (tokens).

2. Lowercasing – Convert all words to lowercase.

3. Punctuation Removal – Remove punctuation marks.

4. Stopword Removal – Remove common stopwords.

5. Stemming – Reduce words to their root form.

6. (Optional) Lemmatization – Normalize words using a dictionary.

 **Input Text Example**
 > Natural Language Processing (NLP) is a subfield of linguistics, computer science, and artificial intelligence concerned with the interactions between computers and human language...

 ***Expected Output:***

- Tokens after step 1

- Tokens after steps 2–3

- Tokens after stopword removal

- Tokens after stemming

## Homework 2 – 10 RegEx Problems

Objective: Learn and apply regular expressions for different text tasks.

***Problems:***

1. Extract Email Addresses

2. Validate Phone Numbers

3. Extract Dates (DD/MM/YYYY, DD-MM-YYYY)

4. Find Repeated Words

5. Extract Hashtags

6. Validate Password Strength

7. Extract URLs

8. Replace Multiple Spaces with a Single Space

9. Extract Quoted Text

10. Validate IP Addresses

**Sample Example (Problem 1 – Extract Email Addresses):**

Text:
> Contact us at support@example.com or sales@company.org

***Output***

- support@example.com
- sales@company.org

## Homework 3 – Text Preparation and Cleaning

Objective: This homework focuses on the analysis and cleaning of the Coachella festival tweets dataset. The main goal was to remove unwanted elements from the data and make it more suitable for analysis.

***The following operations were performed:***

1. Extraction of Hashtags and Emails: All hashtags and email addresses from each tweet were extracted and stored in new, separate columns named "hashtags" and "emails" respectively.

2. Text Cleaning: A series of functions were applied to clean the tweet text, including:

- Removal of usernames (@) and links (http, https).

- Removal of non-ASCII symbols (e.g., emojis).

- Conversion of text to lowercase.

- Removal of stop words, numbers, and special characters (punctuation, etc.).

As a result, a cleaned dataset was created, ready for further analysis.


