# Regex Tutorial - Matching an Email Address

## Introduction
A regex, or regular expression, searches for matching values and/or patterns within a string. Below is a tutorial on how to use regex components to search for an email address.

## Summary
```
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ 
```
This regex tutorial will go over matching an email address. Each component has a role to check that the user enters an email address in the given format. In this case, the email begins with characters followed by an @ symbol and checks for .com, .net, .org, etc. 

The regex is case sensitive. The regex is global, meaning it will check for all matches in the string. The regex is not multiline, meaning it will not check for matches across multiple lines.

## Table of Contents
### [1.  Anchors](#anchors)
### [2. Quantifiers](#quantifiers)
### [3. OR Operator](#or-operator)
### [4. Character Classes](#character-classes)
### [5. Flags](#flags)
### [6. Grouping and Capturing](#grouping-and-capturing)
### [7. Bracket Expressions](#bracket-expressions)
### [8. Greedy and Lazy Match](#greedy-and-lazy-match)
### [9. Boundaries](#boundaries)
### [10. Back-references](#back-references)
### [11. Look-ahead and Look-behind](#look-ahead-and-look-behind)
### [12. Author](#author)

# Regex Components
## Anchors
#### "^" - this anchor checks for the beginning of the string. (used in this example)
#### "$" - this anchor checks for the end of the string. (used in this example)
## Quantifiers
#### "+" - this quantifier checks for one or more of the preceding character. (used in this example)
#### "{2,6}" - this quantifier checks for a range of characters. (used in this example)
## OR Operator
#### "|" - this operator checks for either the preceding or following character. (not used in this example)
## Character Classes
#### "\d" - this character class checks for a digit. (used in this example)
#### "." - this character class checks for any character except a new line. (used in this example)
#### "\w" - this character class checks for a word character. (not used in this example)
## Flags
#### "g" - this flag checks for global matching. (used in this example)
#### "i" - this flag checks for case insensitive matching. (not used in this example)
#### "m" - this flag checks for multiline matching. (not used in this example)
## Grouping and Capturing
#### "( )" - this grouping and capturing checks for a group of characters. (used in this example)
## Bracket Expressions
#### "[ ]" - this bracket expression checks for a range of characters. (used in this example)
## Greedy and Lazy Match
#### "?" - this greedy and lazy match checks for zero or one of the preceding character. (not used in this example)
## Boundaries
#### "\b" - this boundary checks for a word boundary. (not used in this example)
## Back-references
#### "\1" - this back-reference checks for the first captured group. (not used in this example)
## Look-ahead and Look-behind
#### "(?= )" - this look-ahead checks for a match that is followed by a specific string. (not used in this example)
#### "(?<= )" - this look-behind checks for a match that is preceded by a specific string. (not used in this example)
 
# Author
Patrick McKnight - an aspiring web developer who is currently attending a UCSD Extension Full Stack Bootcamp. 
Targeted completion date: June 2023

GitHub: https://github.com/patrickmc19