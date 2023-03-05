# Recipe-Chatbot

Please refer to the points stated herein below which may help to understand as to how I have approached the project and done the work accordingly;

1.Website scraped: https://www.indianhealthyrecipes.com/
2.Libraries used: 
      	from tkinter import *
	import requests
	import tkinter as tk
	import requests	import nltk
	from PIL import ImageTk, Image
	nltk.download('punkt')
	nltk.download('stopwords')
	nltk.download('wordnet')
	nltk.download('omw-1.4')
	nltk.download('averaged_perceptron_tagger')
	from nltk.tokenize import word_tokenize
	from bs4 import BeautifulSoup
	from bs4 import BeautifulSoup
	from nltk.metrics import BigramAssocMeasures
	from nltk.collocations import BigramCollocationFinder

3. Front end: Used Tkinter library in python to make User Interface.
•	Two entries are taken from user as per requirement.
•	One textbox displays all the information.
•	Image is displayed in a separate window.

4. Backend: 
    •Scraping from the website with the use of BeautifulSoup.
    •Fetching the ingredients and recipe separately.
    •Questions that I have prepared this program for:

     1.	What is the first step?
     2.	What is the previous step?
     3.	What is the next step?
     4.	What is the quantity/measure of _______?
     5.	What are the ingredients for a particular group for example “What are the ingredients for gravy in Palak paneer?”
     6.	What is the duration of the recipe?
     7.	What are the tools used?


I have also explored doing the code for audio note for answering the query but its not assembeled in the given code since it wasnt asked.
However I can send it once we get approval from your side to assemble that as well. We can show it to you on viva day.




 
