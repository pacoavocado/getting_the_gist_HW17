# Getting the Gist: A Regex Tutorial

This tutorial will explain how to match emails using a regex.  
`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/` 

The above expression will be the example for this tutorial.

## Summary

A regular expression (regex) is a sequence of characters that are used to specify the paramiters of a search pattern.  Regex patters are used in "find" and "replace" operations in string searching algorithms.

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

An anchor is a ^ or $, which will either preceed or follow a string.  The ^ in this expression indicates the beginning of the string to match, and the $ indicates the end of the string.

### Quantifiers

The quantifiers in this expression are the + operators, they connect the users email name, their email service, and the ".com".  A second quantifyer is {2,6} at the end of the expression, they are allowing matches between 2 and 6 lowercase charactors in the previous charater set.

### Grouping Constructs



### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
