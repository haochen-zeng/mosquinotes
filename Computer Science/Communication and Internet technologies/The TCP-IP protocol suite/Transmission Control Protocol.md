---
date: 2023-09-05
draft: false
tags:
  - definition
  - computer-science
aliases:
  - TCP
---
# Definition

A [[Protocol]] that delivers data through networks.

# Notes

- Allows applications to exchange data.
- Establishes and maintains a connection until exchange of data is complete.
- Determines how to break application data into packets.
- Adds packet number to header.
- Sends packets to and accepts packets from the Internet layer.
- Manages congestion avoidance.
- Acknowledges all packets that arrive.
- Detects when a packet has not arrived at destination.
- Handles retransmission of dropped packets.
- Reassembles packets into the correct order.