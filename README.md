# English-words-list
A python code that classifies all words by letter, length, and letter and length.
# To use:
You need to have the python library nltk installed
To do this in your terminal/command prompt type
`pip install nltk`
then in the python shell enter `import nltk` 
Once you've imported nltk type `nltk.download()` and select the words package under corpus or alternatively install all.

 + The are 698 lists to choose from. You can search for words that are a certain length, words that start with a certain letter, or words that start with a certain letter and are a certain length long.

 + If you want a list of all words that start with 'A', you'd type `letterA` into the python shell after running the code. This works for `letterA`, `letterB`, `letterC`, ETC

 + If you want a list of all words that are three letters long, you'd type `letter3` into the python shell after running the code. This works for `letter1 - letter24`

 + If you want a list of all words that are three letters long and start with 'A', you'd type `letterA3` into the python shell after running the code. This works for all 26 letters and up to 24 letter words. 

 + If you want a list of all words type `word_list` into the python shell after running the code.

 + If you want a list of all words that contains the letter 'A' you can enter `conatins_letterA` this works for all 26 letters

So `letterT` gives all words that start with 'T', `letter5` gives all five letter words, and `letterT5` gives all five letter words that start with 'T'

If you want the length of a list do `len(list-name)` for example `len(letterT5)` out puts the length of `letterT5`(695)
