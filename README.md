Booth Multiplier (Verilog)

📌 Overview

This project implements an 8-bit signed Booth multiplier in Verilog, capable of multiplying two signed integers and producing a 16-bit signed product.
It follows Booth's Algorithm for signed binary multiplication, which is efficient for hardware implementations as it reduces the number of addition/subtraction steps needed.

The design is fully modular, starting from basic gates, building up to full adders, adders, subtractors, and finally the Booth multiplication process.

🛠 Features

Signed multiplication of two 8-bit inputs → 16-bit output.

Uses Booth's Algorithm for efficient computation.

Modular design for reusability:

Logic gates (and2, or2, xor2, etc.)

Multi-bit adders and subtractors

Full adder

Booth substep module

Top-level Booth multiplier

Testbench for verification with sample test cases.
🧠 Key Learning Points

Implementation of basic logic gates in Verilog.

Building multi-bit arithmetic circuits from simple gates.

Applying Booth's algorithm in hardware for signed multiplication.

Modular design for clarity and reusability.

Testbench-driven verification.

📜 License

This project is open-source. You may use, modify, and distribute it for educational or commercial purposes.
