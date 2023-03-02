# Fake-News-Detection-Using-Machine-Learning
### **About the Dataset:**

**id**: unique id for a news article               
**title**: the title of a news article                           
**author**: author of the news article                              
**text**: the text of the article; could be incomplete                             
**label**: a label that marks whether the news article is real or fake:                               
  1: Fake news                                                           
  0: real News   
 
### Stopwords:
A stop word is a commonly used word (such as “the”, “a”, “an”, “in”)that a search engine has been programmed to ignore, both when indexing entries for searching
and when retrieving them as the result of a search query.
Stop Words: A stop word is a commonly used word (such as “the”, “a”, “an”, “in”) that a search engine has been programmed to ignore, both when indexing entries for searching 
and when retrieving them as the result of a search query. We would not want these words to take up space in our database, or taking up valuable processing time. For this, we 
can remove them easily, by storing a list of words that you consider to stop words. NLTK(Natural Language Toolkit) in python has a list of stopwords stored in 16 different 
languages
### Stemming       
Stemming is the process of producing morphological variants of a root/base word. Stemming programs are commonly referred to as stemming algorithms or stemmers. A stemming 
algorithm reduces the words “chocolates”, “chocolatey”, and “choco” to the root word, “chocolate” and “retrieval”, “retrieved”, “retrieves” reduce to the stem “retrieve”.                                           
Stemming is a process of reducing a word to its Root word                                                             
**Example :**                                                                       
program  :  program                                                                        
programs  :  program                                                                
programmer  :  program                                                                               
programming  :  program                                                                     
programmers  :  program    
