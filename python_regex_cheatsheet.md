# Python Regular Expressions
## SPECIAL CHARACTERS
- `^` | Matches the expression to its right at the start of a string. It matches every such instance before each \n in the string.
- `$` | Matches the expression to its left at the end of a string. It matches every such instance before each \n in the string
- `.` | Matches any character except line terminators like \n.
- `\` | Escapes special characters or denotes character classes.
- `A|B` | Matches expression A or B. If A is matched first, B is left untried.
- `+` | Greedily matches the expression to its left 1 or more times.
- `*` | Greedily matches the expression to its left 0 or more times.
- `?` | Greedily matches the expression to its left 0 or 1 times. But if ? is added to qualifiers (+, *, and ? itself) it will perform matches in a non-greedy manner.
- `{m}` | Matches the expression to its left m times, and not less.
- `{m,n}` | Matches the expression to its left m to n times, and not less.
- `{m,n}?` | Matches the expression to its left m times, and ignores n. See ? above.