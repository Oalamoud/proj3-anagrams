# proj3-anagrams
Vocabularly anagrams game for primary school English language learners (ELL)


## Overview

A simple anagram game designed for English-language learning students in 
elementary and middle school.  
Students are presented with a list of vocabulary words (taken from a text file) 
and an anagram.  The anagram is a jumble of some number of vocabulary words, randomly chosen.  Students attempt to type vocabularly words that can be created from the  
jumble.  When a matching word is typed, it is added to a list of solved words. 

The vocabulary word list is fixed for one invocation of the server, so multiple
students connected to the same server will see the same vocabulary list but may 
have different anagrams.

## Authors 

Initial version by M Young; to be revised by CIS 399se students. 

Edited Version by Omar Alamoudi. oka(at)cs(dot)uoregon(dot)edu.

## Status

Working on ix 
List of all edited files
* flask_vocab.py
* templates/vocab.html
* COUNFIG.py
* Makefile

## Where to find it 

On ix port 5955

`ix.cs.uoregon.edu/~oka/cis399se/htbin/proj3-anagrams/` 



## To run automated tests 
* `nosetests`
Working correctly
There are currently nose tests for vocab.py, letterbag.py, and jumble.py. 



