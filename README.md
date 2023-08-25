# Speech_Content_Analysis 

I have worrked on this project using NLP Libraries: nltk, stopwords, PorterStemmer, pickle, numpy, pandas,word_tokenize, num2words, etc.
I have attached a ppt file also for better understanding, that  how this code can help in political domain.
Steps:
1. Data in document format(.txt, .html)in folders: Manifestos, Speeches, News Articles, Interviews.
2. Extracting Folder-name and Folder-title from the files using RE to make a folder-list which contain folder-name and path of the folders   
3. Reads the Content of the file and stores in a ‘text’ variable after  stripping any leading or trailing white spaces.


Data Cleaning :

Converting in lower case and Removing Stop-Words using Stopword Library.( Stop words: the, for, is, on, at, etc.)
Removing Punctuations, apostrophe.
Stemming is done using PorterStemmer library: a method in which words are changed to their basic version.
Changed numbers to corresponding words using num2words library.
Tokenization done with the help of Punkit library.

After all the Preprocessing two lists are created :  processed-text[] and processed-title[], and corresponding content will get stored.
               
![image](https://github.com/jeniferr24/Speech_Content_Analysis/assets/89457990/0d97b65e-37de-4d47-a3a3-2672470fc50a)


<img width="449" alt="image" src="https://github.com/jeniferr24/Speech_Content_Analysis/assets/89457990/f80516cc-6de1-402b-948f-76c579470261">

