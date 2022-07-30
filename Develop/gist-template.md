# Title (Regex Tutorial)

Introductory paragraph (replace this with your text)
 
## Summary

Regex or regular expression is a set of characters that define search patterns in a text.
example: 
https?:\/\/(www\.)?[\d-a-zA-Z0-9@:%._\+~#=]{1,256}\.[a-zA-Z0-9()]{1,6}\b([-a-zA-Z0-9()@:%_\+.~#?&//=]*)

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors
Anchors are used at the beginning and end of searches to check if a string fully matches a pattern.

Use the ^ anchor to match the beginning of the text.
Use the $ anchor to match the end of the text.
### Quantifiers
 A range of numbers placed between two curly brackets ({}) that set the minimum and maximum limits for each section of the string.
### Grouping Constructs
Grouping is a pattern that is enclosed in parentheses () and treats multiple characters as one whole unit. 
example: (www\.)?[\d-a-zA-Z0-9@:%._\+~#=] 

### Bracket Expressions
Contains an expression in square brackets []. 
### Character Classes
Searches for set of characters in a string. 
example:
\d searches for and digits.
\D searches for non-digits.
\s searches for spaces/tabs/and new lines. 
\w searches for alphanumeric characters. 

### The OR Operator
OR operator matches characters to the left or right of an operator working as an (and/or)
example: a|A

### Flags
Flags are used at the end of a REGEX. Flags modify parameters of a search. Flags must be written in lower case. 
### Character Escapes

## Author
 Shane Hancock aspiring full stack developer
 https://github.com/shanehancock64
