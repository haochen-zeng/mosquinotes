---
date: 2023-09-05
draft: false
tags:
  - definition
  - computer-science
---
# Definition

A layered collection of [[Protocol|Protocols]] that work together to provide services.

# Notes

For a [[Protocol suite]], the [[Protocol|Protocols]] can be viewed as layers:
- Each layer can only accept input from the next higher layer or the next lower layer.
- There is a defined interface between adjacent layers which constitutes the only interaction allowed between layers.
- A layer is serviced by the actions of lower layers.
- With the possible exception of the lowest layer the functioning of a layer is created by installed software.
- A layer may comprise sub-layers.
- Any [[User]] interaction will take place using [[Protocol|Protocols]] associated with the highest level layer in the stack.
- Any direct access to hardware is confined to the lowest layer in the stack.