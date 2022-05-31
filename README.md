# twitter-helper
This repository contains helper files for getting twitter data from twitter API, reprocessing tweets and other files.

<br/>

### Regular Expressions

Regular expressions are the sequence of characters that specifies a pattern to search in a given text. 

Basic regex characcters:
1) Characters:
- escape character: \
- any character: .
- digits: \d
- not a digit: \D
- word character: \w
- not a word character: \W
- whitespace: \s
- not whitespace: \S
- word boundary: \b
- not a word boundary: \B
- begging of a string: ^
- end of a string: $

2) Groupings
- matches characters in brackets: []
- matches characters not in brackets: [^]
- either or: |
- capturing group: ()

3) Quantifiers
- 0 or more: *
- 1 or more: +
- 0 or 1: ?
- exact number of characters: {}
- range of number of characters: {minimum, maximum}


Few other examples: In r'([a-z])\1+', \1 means backreference in pattern therefore this means find a letter followed by one or more occurences of that same letter.

Sourc:[Link](https://towardsdatascience.com/regular-expressions-clearly-explained-with-examples-822d76b037b4) <br/>
Check the regex here: [Check](https://regex101.com/)
