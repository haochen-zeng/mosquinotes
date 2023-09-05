---
date: 2023-09-01
draft: false
tags:
  - definition
  - computer-science
---
# Definition

A representation of a [[Real number]] that stores a value for the whole part and a value for the fractional part.

# Notes

For example:
```
1   0   1   0   . 1    0    0    0
2^3 2^2 2^1 2^0 . 2^-1 2^-2 2^-3 2^-4
```
8 [[Bit|Bits]] are used, 4 for the whole part and 4 for the fractional part.
`2^3 + 2^1 = 10`, the whole part is 10. `2^-1 = 0.5`, the fractional part is 0.5. `10 + 0.5 = 10.5`, the [[Real number]] is 10.5.