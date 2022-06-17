# Regex Tutorial

Regex or regular expression is a way to parse a sting to validate input. Common instance of Regex usage is validating either email input, or a password.

## Summary

The Regex that I will be explaining is below. the code snippet is to test a password to meet security requirements. 
^(?=.*?[A-Z])(?=.*?[a-z])(?=.*?[0-9])(?=.*?[#?!@$ %^&*-]).{8,}$

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors

The anchors are indicating the start and end of regex code. In this example the Anchors used are '^' and '$'. The '^' indicates a start of a regex code. '$' indicates the termination of a regex code 

### Quantifiers

The quantifier of this regex snippet is {8,} the last part before the end anchor. What this snippet is testing for is the length of the password being at lest 8 characters. 

### OR Operator

This regex code does not have an OR operator. But a OR operator in regex is done with with a single vertical bar '|' instead of two vertical bars '||' used as the OR operator in programming. 

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
