# Email Validation With Regex

This challenge will be explaining how we can use regex to validate an email.

## Summary

The regex I will be explaining is the following: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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

All regex have two anchors that start and end the expression. The beginning character is a carrot (^) and the ending character is a dollar sign ($). They can both be seen in the example regex provided previously.

### Quantifiers

Set the limits of the string that your regex matches (or an individual section of the string). They frequently include the minimum and maximum number of characters that your regex is looking for. In our example they can be seen at the end as {2,6}

### Grouping Constructs

The primary way you group a section of a regex is by using parentheses (()). Each section within parentheses is known as a subexpression. Looking at our example, we can see three subexpressions.

### Bracket Expressions

Anything inside a set of square brackets ([]) represents a range of characters that we want to match. In our example we see [a-z0-9] inside the first bracket section. That means that it will be looking for letters between a-z and numbers between 0-9.

### Character Classes

Defines a set of characters, any one of which can occur in an input string to fulfill a match. In our example we see \d wich means any Arabic numeral digit. That is the equivalent of the bracket expression [0-9].

### The OR Operator

The OR operator is not seen in our example, but the OR operator is represented by the (|) symbol and means literally "or". For example (a|b) would read "a or b".

### Flags

Flags are not seen in our example, but flags are placed at the end of a regex, after the second slash, and they define additional functionality or limits for the regex. Three examples of flags would be: g: Global search.the regex should be tested against all possible matches in a string., i: Case-insensitive search. case should be ignored while attempting a match in a string, and m: Multi-line search. a multi-line input string should be treated as multiple lines.

### Character Escapes

The backslash (\) in a regex escapes a character that otherwise would be interpreted literally. This is common when looking for strings with special characters that are the same as a particular component of a regex. Our example has a few. One for example: \.-

## Author

My name is Allison Farrell and I am a fullstack developer based in Savannah,GA. My gitHub account is:
https://github.com/Afarrell95
