level-1-getting-started/inside-a-computer-system.md

# Inside a Computer System

**Date:** 16/09/2026
**Room:** TryHackMe — Inside a Computer System
**Path:** Pre-Security → Computer Fundamentals
**Type:** Conceptual

## What the room was about
An overview of the physical components that make up a computer and how they work together.

## Key concepts I learned

### Motherboard
The main circuit board that connects all the other components.

### CPU (Central Processing Unit)
The "brain" of the computer. It executes instructions.

### RAM (Random Access Memory)
Temporary, fast memory used while the computer is running. Data is lost when the power goes off.

### Storage (HDD / SSD)
Permanent storage for files and the operating system. Data survives power off.

### GPU (Graphics Processing Unit)
Handles graphics and visual calculations. Also used for AI/ML workloads.

### Power Supply
Converts AC power from the wall into DC power the computer uses.

## How the components work together
The power supply provides electricity to all components. The motherboard connects all the components. The CPU processes the information. The GPU handles all the calculations related to graphics and visuals, and renders the image. The RAM helps with this process, and the data is stored in the SSD/HDD.

## Why this matters for a SOC Analyst
Understanding the hardware helps when investigating incidents. For example: a machine running out of RAM may crash and produce errors that look like attacks. Disk encryption (BitLocker) depends on hardware. Physical access to a machine is a real security risk.

## What surprised me
Understanding these components helps me detect false positives. A RAM error is not the same as a real attack, but both can look similar in a log if you don't understand the hardware.
