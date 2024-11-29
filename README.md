Lilala's Lexicon is a dictionary app whereby users can look up the definitions, phonetics and an example of any word in English.
The app is able to do so by fetching Data from the Free Dictionary API

Features
-  Search for english words to retrieve: Definitions, Phonetics and Part of speech

Technologies Used 
- Programming Languages: HTML, CSS and Javascript
- API used: Free Dictionary API. 

Api Documentation
- Free Dictionary API  https://dictionaryapi.dev/

How to access Lilala's Lexicon?
Locally:
- git clone https://github.com/lilalajemima/api_summative.git 
Navigate to the directory Lilala_Lexicon
Open the index html possibly with the aid of a live server extension or with your browser.

Online
- By using this link https://www.lilalajemima.tech

Challenges I had and Solutions
- Handling Errors
Users initially  received no feedback when entering invalid words -> Added error handling to display a user-friendly error message when a word is not found.

- Missing Data
Some words do not have full information like parts of speech -> The script has conditional rendering so only available information is displayed preventing the app from crashing.

Credits
- API: Free Dictionary API
Google Fonts: Source Code Pro
