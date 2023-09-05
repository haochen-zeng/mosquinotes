---
date: 2023-09-05
draft: false
tags:
  - definition
  - computer-science
---
# Definition

A communication method where data is divided into smaller units called packets and transmitted over the network.

# Notes

- Packets can travel along different routes from node to node.
- Make full use of the available capacity by using alternative routes.
- Packets are reassembled in the correct order at the receiver's end.
- Doesn't matter if data arrives out of order.
- Must wait until the last packet is received to put the data back together.
- Allows for error checking.
- Real time transmission is not required.
- Bandwidth can be shared.