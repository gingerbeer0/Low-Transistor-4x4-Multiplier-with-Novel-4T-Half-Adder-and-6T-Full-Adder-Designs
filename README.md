# Low-Transistor-4x4-Multiplier-with-Novel-4T-Half-Adder-and-6T-Full-Adder-Designs
This project presents a compact and transistor-efficient 4x4 multiplier architecture, utilizing novel custom-designed 4-transistor half adders and 6-transistor full adders. The architecture is optimized for low-area VLSI implementations while maintaining full functional correctness and scalability.

## 🔧 Overview

This repository contains a custom-designed 4x4 multiplier using area-optimized logic gates:

- **Half Adder**: 6T with inverter (4T without inverter)
- **Full Adder**: 12T with inverter (6T without inverter)

The architecture is tailored for low-transistor count implementations suitable for VLSI layout optimization and educational purposes.

---

## 🧱 Custom Cell Design

### Half Adder
![image](https://github.com/user-attachments/assets/d3de9c4d-1575-48a7-912a-f59506bf92e8)

- **Transistor Count**:
  - **With inverter**: 6 transistors
  - **Without inverter**: 4 transistors
- Implements XOR and AND using pass-transistor logic.

### Full Adder
![image](https://github.com/user-attachments/assets/6db95dfd-9858-459c-ba1c-bf046f5daabe)

- **Transistor Count**:
  - **With inverter**: 12 transistors
  - **Without inverter**: 6 transistors
- Sum and carry logic optimized with minimal transistor stages.

---

## 📐 4x4 Multiplier Structure
![image](https://github.com/user-attachments/assets/e98d90a1-08c8-40de-b87b-28590246d128)

The multiplier is based on the conventional array multiplier approach:

- 16 Partial Product Generators (AND gates)
- Custom Half/Full Adders used in partial product addition
- Optimized interconnect for low-area layout

layout
![image](https://github.com/user-attachments/assets/4be912db-6074-4e29-b338-016feaf62b3b)


---

## 📁 Simulation Results
-(1101/0010)
 ![image](https://github.com/user-attachments/assets/93a8184f-442b-4ff7-a9c4-4da274249d2c)

-(1010/0101) 
 ![image](https://github.com/user-attachments/assets/786cf793-d605-434e-a8b1-df681da286ec)

-(1111/0100)
 ![image](https://github.com/user-attachments/assets/8f6cbf6e-f082-4526-9248-cf915574bdec)

-(0011/1111)
 ![image](https://github.com/user-attachments/assets/75d5dfb7-7d4d-4cf2-9af6-8dee8190209c)

-(1001/0001)
 ![image](https://github.com/user-attachments/assets/a8b20a09-5282-4d15-9cf2-c403db47632e)



