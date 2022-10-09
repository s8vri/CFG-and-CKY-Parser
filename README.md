# CFG and CKY Parser
In this assignment the Cocke-Kasami-Younger (CKY) algorithm for bottom-up CFG parsing was implemented
and applied to the word and the parsing problem of English.

The CKY Parser was implemented based on the ATIS CFG available in the NLTK datapackage, together with 98 
test sentences. ATIS CFG is a grammar which stems from a project dealing with implementing spoken lan-
guage processing systems in the airline industry – the Airline Travel Information System.

*Output:*

- trees_number_txt file containing the parsing results (number of parses per sentence) with one line of the 
form sentence\t#parses for each test sentence, where \t is a tab character

- images_parse_trees.pdf containing pictures of the parse trees for an ATIS test sentence with two to five parses. 
