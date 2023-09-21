---
date: 2023-09-19
draft: false
tags:
  - definition
  - computer-science
aliases:
  - CA
---
# Definition

An organization that acts to validate identities and bind them to a [[Key]] pair with [[Digital certificate|Digital certificates]].

# Notes

Steps taken for a person to obtain a [[Digital certificate]]:
1. The person is a would-be receiver.
2. The person has a [[Key]] pair.
3. Confirms the identity of a person.
4. The person's [[Public key]] is given.
5. Creates a [[Digital certificate]].
6. Writes the person's [[Public key]] into the [[Digital certificate]].
7. Uses [[Encryption]] with its own [[Private key]] to add a [[Digital signature]] to the [[Digital certificate]].
8. This [[Digital certificate]] is given to the person.
9. The person posts the [[Digital certificate]] onto a website.