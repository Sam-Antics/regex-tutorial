# Strong Password Regex Tutorial

A regex (or, regular expression) is a sequence of characters that defines a search pattern that helps users match, locate, or manage text. Common use cases include matching strings of text, finding and replacing operations, and input validation. For example, with regex you can easily check a user's input for common misspellings of a particular word. The regex pattern consists of one or more character literals and/or "meta" characters, which are stand-ins to represent possible text combinations.

## Summary
This tutorial covers the following regex, which tests for a strong password.
```
/^(?=^.{8,}$)((?=.*[A-Za-z0-9])(?=.*[A-Z])(?=.*[a-z]))^.*$/
```
 In brief summary, the regex checks passwords against the following criteria: 
 - password must contain one lowercase letter
 - password must contain one uppercase letter
 - password must contain one number
 - password must be at least 8 characters long.

The tutorial will break down this regex by its components, describing the functionality and providing examples for each snippit.
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

### Quantifiers

### OR Operator

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
