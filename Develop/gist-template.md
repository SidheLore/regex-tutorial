# Regex Tutorial: Matching an HTML Tag

Regular expressions, or regex, specify textual search patterns. They are used in search engines, text, editors, and word processors, and they are used to extract information.

## Summary

This article will explain the regex components of matching an HTML Tag. It will focus on the following regular expression:
```
/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/
```
## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)

## Regex Components

### Anchors
Anchors reveal where in a string matches can occur. In this regex, two anchors are used: the `^` anchor and the `$` anchor. The `^` is used at the beginning of a string, and a `$` is used at the end of a string. 

### Quantifiers
Quantifiers are used to specify the maximum and minimum number of characters it is looking for in the string. A `?`, for example, will match the preceding character in zero or one instance. A `+` will match it one or more times.

### OR Operator
OR operators `|` are used to match one component or another.

### Character Classes
Character classes define the characters to be matched. The `\s` class matches a space or tab, the `\d` class matches digits, the `\w` class matches alphanumerical characterss, and the `\.` matches any character at all.

### Flags
Flags modify searching behavior. The `i` flag matches the word/character given, regardless of capital or lowercase letters. The `g` flag matches each word/character given. The `m` flag matches the first word/character given at the beginning of a line. 

### Grouping and Capturing
Parentheses are used to group and organize.

### Bracket Expressions
Bracket expressions define the groups of characters to be matched. For example, `[a-z]` is used to match any lowercase letter in the alphabet.

## Author

Hi, everyone. My name is Jessica, and I am studying full-stack web development. Follow me on GitHub: [SidheLore](https://github.com/SidheLore). 