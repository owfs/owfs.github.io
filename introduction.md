---
title: Introduction
---
## OWFS?

OWFS is an easy way to use the powerful 1-wire system of Dallas/Maxim.

The name means 1-Wire File System, although the File System part is something we try to move away from.

## What is 1-Wire?
*1-wire* is a:
* communication protocol
* wiring scheme
* assortment of devices and "iButtons"

The design and control of the protocol is from Dallas Semiconductor (part of Maxim Semiconductor) which has application notes, software, and devices for sale.

The 1-wire protocol is marketing-speak. It is actually 2 wires, one for ground.

The active wire conducts data and power!

### What are the advantages?
* Simple connections
* Self configuring
* Cheap and flexible devices

### Ok, Disadvantages?
* Relatively slow
* Needs an adapter (bus master) and software (like OWFS).
* Have to be a little careful in wire layout to avoid signal reflections
