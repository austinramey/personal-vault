# REGEX
- ==Regular Expression:== a String that describes a search pattern for matching characters in other Strings
- ==Matches==: a string method to check if the string given matches the given regex
- Predefined character classes:

| Character | Matches                       |
| --------- | ----------------------------- |
| \d        | any digit                     |
| \w        | any word character            |
| \s        | any white-space character     |
| \D        | any nondigit                  |
| \W        | any nonword character         |
| \S        | any non-white-space character |
- Quantifiers

| Quantifier | Matches                                     |
| ---------- | ------------------------------------------- |
| *          | Matches zero or more occurs. of the pattern |
| +          | Matches one or more occurs.                 |
| ?          | Matches zero or one occurs.                 |
| {n}        | Matches exactly n occurences                |
| {n,}       | Matches at least n occurs.                  |
| {n,m}      | Matches between n and m (inclusive) occurs. |
//
- Quantifiers are greedy, meaning they will match as many occurs. as long as the match is still successful
- 