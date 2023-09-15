---
date: 2023-09-11
draft: false
tags:
  - definition
  - computer-science
aliases:
  - SIMD
---
# Definition

Processing of parallel data input requiring one control unit instructing multiple processing units.

# Notes

- Used in modern GPUs.
- A single instruction is executed on multiple different pieces of data.
- These instructions can be performed sequentially, taking advantage of [[Pipelining]].
- Very efficient where you need to perform the same instruction on large amount of data.
- Limited to specific applications.