# Getting the Gist: A Regex Tutorial

This tutorial will explain how to match emails using a regex.  
`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/` 

The above expression will be the example for this tutorial.

## Summary

A regular expression (regex) is a sequence of characters that are used to specify the paramiters of a search pattern, usually for validation purposes.  Regex patters are used in "find" and "replace" operations in string searching algorithms.

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

An anchor is a ^ or $, which will either precede or follow a string.  The ^ in this expression indicates the beginning of the string to match, and the $ indicates the end of the string.

### Quantifiers

The quantifiers in this expression are the + operators, they connect the users email name, their email service, and the ".com".  A second quantifier is {2,6} at the end of the expression, they are allowing matches between 2 and 6 lowercase characters in the previous character set a-z`\`.

### Grouping Constructs

Grouping constructs are formed within parentheses (()).  Each group of parentheses within a parentheses is a sub expression.  In the example expression 
`([a-z0-9_\.-]+)` and `([\da-z\.-]+)` and `([a-z\.]{2,6})` are capturing constructs because there is not a ?: beginning within the expression.  A non-capturing construct would not be usable as back reference.

### Bracket Expressions

The bracketed expressions in the example `[a-z0-9_\.-]` and `[\da-z\.-]` and `[a-z\.]` are for character validation.  The first bracket would be used to authenticate a users email that contains any character and/or number.  The second bracketed expression contains `\da-z\.-` this allows for a single number and any combination of characters.  The last bracketed expression `[a-z\.]` allows for any letters between a-z there is a quantifier on the outside of this bracket expression that would limit the length range.

### Character Classes

This expressions uses `\d` as a character class, it validates a single digit may be used within an expression.

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
