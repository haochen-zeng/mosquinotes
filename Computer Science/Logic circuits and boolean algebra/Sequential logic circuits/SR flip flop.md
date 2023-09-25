---
date: 2023-09-15
draft: false
tags:
  - definition
  - course-name
aliases:
  - Latch
---
# Definition

A flip flop with two inputs, one is S and other is R.

# Notes

- An example of [[Sequential circuit]].
- One [[Bit]] memory.
- Can be constructed with two NAND gates or two NOR gates.

The truth table with NOR gates:
```
S R Q Q'
0 0 1 0
0 0 0 1
0 1 0 1
1 0 1 0
1 1 0 0 # Invalid
```

The truth table with NAND gates:
```
S R Q Q'
0 0 1 1 # Invalid
0 1 1 0
1 0 0 1
1 1 0 1
1 1 1 0
```