# 7-Segment Binary to Hexadecimal Decoder using Logic Gates

##  💡 Overview

This project implements a 4-bit binary input to hexadecimal output displayed on a 7-segment display.  
The logic for each segment (a–g) is derived and minimized using Karnaugh Maps (K-Maps), and the final simplified Boolean expressions are implemented using basic logic gates.

---

##  🎯 Objective

To satisfy my personal interest, I aimed to design a combinational circuit that:

- Accepts a 4-bit binary input (A, B, C, D)
- Displays the corresponding hexadecimal digit (0–F) on a 7 segment display for output

---

##  ⚙️ Approach

1. Constructed the truth table for all hexadecimal values (0–F).
2. Created separate K-Maps for each of the 7 segments (a–g).
3. Grouped minterms to obtain simplified Boolean expressions.
4. Derived minimized equations for each segment.
5. Implemented the equivalent gate-level logic design per segment.

---

##  🗺️ K-Map & Truth Table

All K-Maps for segments (a–g) are included below:

<!-- Insert images here -->
<!-- Example:
![Segment A K-Map](images/seg_a.png)
-->

---

##  🎥 Demonstration

<!-- Add demo video link here -->

---

##  🛠 Tools Used

- CircuitVerse – Circuit simulation and logic implementation  
- Excalidraw – Karnaugh Map visualization and grouping  
- Google Sheets – Truth table construction  
