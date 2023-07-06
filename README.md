# Problem Search Engine using TF-IDF
## Problem statement
The main objective of this project is to develop an intelligent and efficient search engine that can access coding problems from LeetCode. The user should be able to input specific keywords and be presented with a list of suitable coding problems that match their search criteria. The search engine should ensure that the problems returned are relevant and accurate.
## Solution
The proposed search engine will be built around the **TF-IDF algorithm** to index coding problems efficiently. To accomplish this, the following steps are undertaken:
- Scraping problems of LeetCode using a Python-based web scraping tool like **Selenium**.
- Implementing the TF-IDF algorithm to handle search functionality.
- Pre-processing the scraped data to extract relevant text information and creating a dictionary of terms from the data and calculating the inverse document frequency for each term.
- Applying the TF-IDF weighting scheme to the data.
- Integrating the search algorithm and server-side functionality with the user interface.

## Running Code locally
To run the code locally run following commands in terminal
(You must have python interpreter installed in your system)
1) Installing flask
```bash
 pip install flask
```
2) Installing chardet
```bash
 pip install chardet
```
3) For scrapping questions dependencies run following:
```bash
 pip install selenium
```
4) Running app.py
```bash
 flask --app app run
```
You will get a url in console, follow url to see it running.

## Live Website

https://problem-search-using-tf-idf.onrender.com
