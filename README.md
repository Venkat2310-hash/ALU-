# 🧮 32-Bit ALU Design in Logisim

A complete 32-bit Arithmetic Logic Unit (ALU) designed using Logisim. This circuit performs core arithmetic and logical operations and is capable of handling 32-bit binary input operands.

---

## 🎯 Objective

To design and simulate a 32-bit ALU that mimics the functional behavior of a processor’s execution unit, handling integer operations with accurate bitwise and arithmetic logic.

---

## ⚙️ Features

- **32-bit Inputs**: Operand A and Operand B
- **Operations Supported**:
  - Addition
  - Subtraction
  - Multiplication
  - Division
  - Bitwise AND, OR, XOR, NAND
  - Multiplexed output routing
- **Control Line Input**: Determines operation via decoder
- **Modular Blocks**:
  - 32-bit Adder/Subtractor
  - 32-bit Logic Gates
  - MUX to select output
- **Register and Control Signals**:
  - Select
  - Load
  - Clear

---

## 📂 Files

| File | Description |
|------|-------------|
| `alu_design.circ` | 32-bit ALU design in Logisim |
| `alu_screenshot.png` | Rendered image of the ALU |
| `truth_tables.txt`  | Binary control mapping to operation |
| `README.md` | You’re reading it ✔️ |

---

## 🛠 Tools Used

- **[Logisim](http://www.cburch.com/logisim/)** – Circuit simulation
- Control logic via decoder and MUX
- Register file for operand storage

---

## 🚀 Possible Extensions

- Add Overflow, Zero, Carry-out flags
- Pipelined version for simulation of instruction execution
- Integration with control unit in CPU datapath

---

## 👨‍💻 Developed By

**Venkat Narasimha**  
📧 venkatsimha2310@gmail.com
