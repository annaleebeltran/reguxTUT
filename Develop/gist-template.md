# ReguxTut How to match an HTML tag

This is a tutorial on how to match an HTML tag using regex. The regex will match the opening and closing tags of an HTML element. The regex will also match the content between the opening and closing tags. The regex will not match the content of the tag if the tag is self-closing.

## Summary: A quick look at the regex

A Regex or known as a regular expression is a sequence of characters that defines a search pattern. Usually these patterns are used by string-searching algorithms for "find" or "find and replace" on string operators. It will also look for inputs of validation. It is commonly used in theoretical computer science thougt processes.

Using a string of regux, this code looks for a match HTML tag.

Ex: /^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/

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

Annalee is a full stack developer, please see her work at:
