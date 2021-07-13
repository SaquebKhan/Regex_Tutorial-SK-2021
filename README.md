# Regex Tutorial-SK-2021

This tutorial is to explain what regex is. Regex is a type of search pattern that shows a sequence of characters. It can help identify patterns in strings and/or replace sequences in that string.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping](#grouping)
- [Bracket Expressions](#bracket-expressions)
- [Refrences](#refrences)

## Regex Components

### Anchors
Anchors are used to start and end a search expression. All the "action" will happen inside of these symbols. A example of this are shown below:
 * `^` : Beginning of input
 * `$` : End of a input

### Quantifiers
Quantifiers specify the number of instances of a given character or group that must be present in the input to be found.

Symbols with Refrences: 
* `?` : matching to the previous character is optional
    * `https?` : matches (https), (http)
* `+` : match to one or more of the proceeding character
    * `[\da-z\.-]+` : matches a single character (d), (.), (-) or group of letters (a-z) 1 or more times
* `*` : match zero or more of the previous character (combination of `?` and `+`)
    * `([\/\w \.-]*)*` : matches (/) or (//), (w) or (www), (.), (-)
* `{}` : defines how many characters will be searched for
    * `{n}` : n = the total number of characters
    * `{n, }` : n = minimum number of characters being searched for
    * `{n,m}` : m = max number of characters being searched for, n = minimum number of characters being searched for

    * `[a-z\.]{2,6}` : matches 2 - 6 copies of [a-z\.]

### Grouping
Grouping is an important aspect of regEx. It allows you to group various characters together.

For example:

/a[bc]/ will give you a result where a is followed by either a 'b' or a 'c'.

### Bracket Expressions
A bracket expression is a type of expression that shows the characters that contain an email. If the email has a defined range or characters, then it should have a bracket.

### Refrences
- YouTube
- Google
- https://docs.google.com/document/d/1xoX9qDCUaPxAo4fd9K6sweAtOFwq1I6XcixGkqR93iw/edit#heading=h.5a65nmeo9amx

## Author
By Saqueb Khan, If you have any questions please email me (khansaqueb@gmail.com)