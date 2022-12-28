Project Structure

 -CKY_Parser.ipynb

 -trees_number.txt 
 
 -images_parse_trees.pdf
 
 -README.txt
 
The output files are:
- trees_number.txt, contains only filtered parse trees with 2-5 parses
- trees_number.txt, contains the 98 test sentences and the number of parses for each sentence

The CKY_Parser.ipynb file contains all the code for the CKY recognizer and parser
 
 Requirements: Python 3.8.5
               nltk 3.5
               collections
               itertools
               datetime
               
System Details: OS Ubuntu 20.04.1 LTS
 		 OS type 64 bit
 		 
The runtime for the recognizer is: 43.738257 seconds
The runtime for the recognizer and parser is: 49.783717 seconds

Since drawing a tree with nltk.draw opened the trees in many windows, I commented it and used t.pretty_print() instead.
