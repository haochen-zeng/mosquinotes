---
date: 2023-08-30
draft: false
tags:
  - definition
  - computer-science
---
# Definition

A file that contains records that are ordered.

# Notes

There has to be a key for which the values are unique and sequential but not necessarily consecutive.

To add a new [[Record]]:
1. Read file sequentially.
2. Each [[Record]] is written to a new file.
3. Continued until the appropriate position for the new [[Record]] is reached.
4. The new [[Record]] is then written to the new file.
5. The remaining records in the old file are copied in.