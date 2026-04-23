# Lab Assignment 2: Packet Flow Visualization

---

## Description

This assignment demonstrates how packets move in a local network using Simulation Mode in Cisco Packet Tracer. It focuses on understanding ARP resolution, ICMP communication, and how switches learn MAC addresses.

---

## Steps to Perform the Experiment

1. Create a network with:

   * 1 Switch
   * 3 PCs

2. Connect all PCs to the switch using copper straight-through cables

3. Assign IP addresses:

   * PC1 → 192.168.20.1
   * PC2 → 192.168.20.2
   * PC3 → 192.168.20.3

4. Switch to Simulation Mode

5. Apply filters:

   * ARP
   * ICMP

6. Perform first ping:

   * Send packet from PC1 to PC2
   * Observe ARP request and reply followed by ICMP

7. Perform second ping:

   * Send packet again from PC1 to PC2
   * Observe only ICMP packets

8. Observe switch behavior:

   * Initial broadcast
   * Later direct communication

---

## Learnings

* ARP is used to map IP address to MAC address
* First ping includes ARP process, making it slower
* Second ping is faster due to ARP caching
* Switch learns MAC addresses dynamically
* Broadcast is used only when destination is unknown
* Simulation Mode helps visualize packet flow clearly

---

## Files Included

* Packet Tracer File (.pkt)
* Screenshots of packet flow
* README documentation

---
