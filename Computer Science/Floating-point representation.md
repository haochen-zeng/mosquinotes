---
date: 2023-09-01
draft: false
tags:
  - definition
  - computer-science
---
# Definition

A representation of a [[Real number]] that stores a value for the [[Mantissa]] and a value for the [[Exponent]].

# Notes

- [[Mantissa]] and [[Exponent]] are represented in [[Two's complement]] form.

The generalized format:
$$
\pm M \times R^E
$$
`±M` is the [[Mantissa]]. `E` is the [[Exponent]]. `R` is the [[Radix]], which has an implied value of 2.

For example:
```
0   0   1   0   1   0   0   1   1   1
2^4 2^3 2^2 2^1 2^0 2^4 2^3 2^2 2^1 2^0
```
10 [[Bit|Bits]] are used, 5 for the [[Mantissa]] and 5 for the [[Exponent]].
`2^2 + 2^0 = 5`, the [[Mantissa]] is 5. `2^2 + 2^1 + 2^0 = 7`, the [[Exponent]] is 7. `5 * 2^7 = 640.0`, the [[Real number]] is 640.