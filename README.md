# 🔢 8-Bit Binary to BCD Converter using Double Dabble (Manual Logic in Proteus)
This project implements the Double Dabble algorithm (Shift-Add-3) to convert an 8-bit binary number into its 3-digit BCD equivalent, using manual logic gate design (no shift register ICs). The entire system was built and simulated in Proteus using logic gates, adders, comparators, and 7-segment displays.

📌 Objective
To design and simulate a pure logic-based hardware circuit that performs binary to BCD conversion using the Double Dabble algorithm, without relying on microcontrollers or shift-register ICs.

🧠 Concept: Double Dabble Algorithm
The Double Dabble (also known as Shift-and-Add-3) algorithm is a widely used method to convert binary numbers into Binary Coded Decimal (BCD). The basic idea is:

Shift all bits left.

If any BCD digit is ≥ 5, add 3 before the next shift.

Repeat the process for each input bit.

This mimics the behavior of decimal counting within a binary system.

🛠️ Components Used
Logic Gates (AND, OR, NOT, XOR)

Binary Comparators (e.g., 7485)

Adders for Add-3 logic (e.g., 7483)

3 x 4-bit Registers (manual wiring)

Multiplexers (for control where needed)

7-Segment Displays (Common Cathode)

Clock Signal (manual or automatic)

🔧 Implementation Highlights
No shift register ICs used — bit shifting and register logic implemented manually with gates.

BCD correction logic (Add-3) handled using comparators and conditional adders.

The circuit displays 3-digit decimal output for any 8-bit binary input (00000000 to 11111111).

Neatly modularized circuit for easy debugging and reuse in larger digital systems.

🎯 Learning Outcomes
Mastered the practical logic implementation of the Double Dabble algorithm.

Gained deep understanding of bitwise operations at gate level.

Practiced digital logic design, simulation, and troubleshooting in Proteus.

🖼️ Preview
Example: Binary input 11001010 → BCD Output: 202

💡 Possible Extensions
Automate with shift-register ICs (e.g., 74LS299)

Expand for 10-bit or 12-bit inputs

Add a decimal input interface using DIP switches or keypad


🤝 Credits
Designed by Shahab
Bachelor of Computer Engineering – NUST


