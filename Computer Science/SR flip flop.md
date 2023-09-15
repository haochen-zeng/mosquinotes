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
- One bit memory.
- Can be constructed with two NAND gates or two NOR gates.

With NOR gates:
```mermaid
flowchart LR
   R --> A[NOR]
   S --> B[NOR]
   A[NOR] --> Q
   B[NOR] --> Q'
   A --> B
   B --> A
```
```
S R Q Q'
0 0 1 0
0 0 0 1
0 1 0 1
1 0 1 0
1 1 0 0 # Invalid
```

With NAND gates:
```mermaid
flowchart LR
   R --> A[NAND]
   S --> B[NAND]
   A[NAND] --> Q'
   B[NAND] --> Q
   A --> B
   B --> A
```
```
S R Q Q'
0 0 1 1 # Invalid
0 1 1 0
1 0 0 1
1 1 0 1
1 1 1 0
```