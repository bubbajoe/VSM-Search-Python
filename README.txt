VSM Search by Joe Williams

About

VSM Search is a Vector Space Model Search. My
implementation of VSM uses the term frequency 
and the inverse document frequency for each 
word per document, then averages all of the 
words by the document to determine which 
document is more relevent. 

Installing

Make sure to run "vsm.py" with Python 3.6.3^.
Make sure the nltk data is downloaded
by running ```nltk.download()``` in python.
A pop-up window should appear and you can 
either install everything or go on the 
'all packages' and download the name - 
'Word Lists' id-'words' item.

Usage

Once you run the file. You should be prompted 
to enter your search query. you can put as many 
words as you would like and separtate them with 
spaces. Most special characters are removed except 
for '. You will be prompted if one of your words 
is a stem word. stem words are removed from searches
to accurately score other words. '/exit' to close 
to the application.