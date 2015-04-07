# Markov-Text-Generator
A trigram Markov model to generate random text from wikipedia or file

A second-order Markov Model to generate random text by using a wikipedia page and all linked pages
or a text file. Specify the following as command line options
                        1)Whether it should generate words or characters
                        2)wiki page to extract from
                        3) File paths as command line
                        4) From cache or wikipedia option
                        
If the model is trained by the character, then the probability of a given passage (path as command line option) being generated can be computed (The trained model will not be general enough if it is trained by the word to make this computation).
