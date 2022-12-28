# CFG and CKY Parser
In this assignment the Cocke-Kasami-Younger (CKY) algorithm for bottom-up CFG parsing was implemented
and applied to the word and the parsing problem of English.

The CKY Parser was implemented based on the ATIS CFG available in the NLTK datapackage, together with 98 
test sentences. ATIS CFG is a grammar which stems from a project dealing with implementing spoken language 
processing systems in the airline industry – the Airline Travel Information System.

*Output:*

- trees_number_txt file containing the parsing results (number of parses per sentence) with one line of the 
form sentence\t#parses for each test sentence, where \t is a tab character

- images_parse_trees.pdf containing pictures of the parse trees for an ATIS test sentence with two to five parses. 


# Project Structure

 - CFG_and CKY_parsing.ipynb

 - trees_number.txt 
 
 - README.md
 
*The output files are:*
- trees_number.txt, contains only filtered parse trees with 2-5 parses
- trees_number.txt, contains the 98 test sentences and the number of parses for each sentence

*The CKY_Parser.ipynb file contains all the code for the CKY recognizer and parser*
 
### Requirements: 
               python 3.8.5
               nltk 3.5
               collections
               itertools
               datetime
           
### System Details: 
               OS Ubuntu 20.04.1 LTS
 		    OS type 64 bit
 		 
The runtime for the recognizer is: 43.738257 seconds
The runtime for the recognizer and parser is: 49.783717 seconds

Since drawing a tree with nltk.draw opened the trees in many windows, I commented it and used t.pretty_print() instead.
