# Computer Science Regex Tutorial

## Introduction to CS Regex

Regular expressions, also known as regex, are powerful tools for pattern matching and text manipulation. In this tutorial, we will explore the regex pattern used to match a valid email address. By understanding the components of the pattern and their meanings, you will be able to apply regex in various programming languages and scenarios.

Let's dive into the details of the regex pattern and its components.


## Summary

This tutorial will explain the regex pattern used to match a valid email address. The regex pattern is:
```regex
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
```

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
- `^` asserts the position at the start of the string.
- `$` asserts the position at the end of the string.

### Quantifiers
- `+` matches 1 or more of the preceding token.

### Grouping Constructs
- `()` groups multiple tokens together and creates a capture group.

### Bracket Expressions
- `[a-z0-9_\.-]` matches any lowercase letter, digit, underscore, dot, or hyphen.
- `[a-z\.]` matches any lowercase letter or dot.

### Character Classes
- `\d` matches any digit (equivalent to `[0-9]`).

### The OR Operator
- `|` is used within the brackets to specify alternatives (e.g., `[a-f0-9]{6}|[a-f0-9]{3}`).

### Flags
- No flags are used in this regex pattern.

### Character Escapes
- `\.` escapes the dot character to match a literal dot.

## Author

This is a tutorial written by Emily Soriano

You can find more of Emily's work on her [GitHub profile](https://github.com/So-Emily).


