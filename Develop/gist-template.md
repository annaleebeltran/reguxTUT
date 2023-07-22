# ReguxTut How to match an HTML tag

This is a tutorial on how to match an HTML tag using regex. The regex will match the opening and closing tags of an HTML element. The regex will also match the content between the opening and closing tags. The regex will not match the content of the tag if the tag is self-closing.

## Summary: A quick look at the regex

A Regex or known as a regular expression is a sequence of characters that defines a search pattern. Usually these patterns are used by string-searching algorithms for "find" or "find and replace" on string operators. It will also look for inputs of validation. It is commonly used in theoretical computer science thougt processes.

Using a string of regux, this code looks for a match HTML tag.

Ex: /^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/

## Regex Components

* /
* ^
* <
* [a-z]
* +
* ( ... )
* [^>]
* $

## Regex Explanation

## /
- Every regex is always enclosed in forward slashes. Programming languages recognize this syntax to indicate a regular expression.


## ^
- The caret symbol ^ is used to match the beginning of a string. In this case, the caret symbol is used to match the beginning of the HTML tag.

## <
- " < " stands on it's own, it is not enclosed in any parentheses or brackets. This means that the pattern will match one and only one single open bracket, as expected from an HTML tag.

## [a-z]
- The brackets [ ] are used to define a character class. The character class [a-z] will match any lowercase letter from a to z. This is used to match the first letter of the HTML tag.

## +
- The plus sign + is a quantifier. It will match one or more of the preceding token. In this case, it will match one or more lowercase letters from a to z and marking how many times the character class [a-z] will be matched.

## ( ... )
- The parentheses ( ) are used to define a capturing group. The capturing group will capture the text matched by the regex inside the parentheses. In this case, the capturing group is used to capture the HTML tag.

## [^>]
- The brackets [ ] are used to define a character class. The character class [^>] will match any character that is not a closing bracket thus exculding any matching characters from its class. This is used to match the content of the HTML tag.

## $
- The dollar sign $ is used to match the end of a string. In this case, the dollar sign is used to match the end of the HTML tag. This is the close of the regex tag.

## Author

Annalee is a full stack developer, please see her work at:
https://github.com/annaleebeltran