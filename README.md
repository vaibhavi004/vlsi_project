# 🧠 3-Bit Binary to Gray Code Converter using CMOS & Pseudo-NMOS Logic

This project demonstrates the design and implementation of a **3-bit Binary to Gray Code Converter** using two different logic families: **CMOS** and **Pseudo-NMOS**. Implemented and analyzed using **Cadence EDA tools**, the objective is to compare the power efficiency and complexity of both logic styles — with a focus on low-power applications like **solar-powered autonomous robots**.

---

## 📌 Problem Statement

Design a 3-bit Binary to Gray code converter using **CMOS** and **pseudo-NMOS** logic. Compare their power consumption and assess the suitability of each for power-sensitive applications.

---

## ⚙️ Features

- CMOS and pseudo-NMOS implementations of XOR gates and inverters  
- Hierarchical schematic design using Cadence tools  
- Transient analysis and power consumption evaluation  
- Truth table verification of Binary to Gray conversion  
- Power efficiency comparison for low-power VLSI applications  

---

## 🔍 Conversion Logic

The converter follows the standard Binary to Gray code logic:

- G2 = B2  
- G1 = B2 ⊕ B1  
- G0 = B1 ⊕ B0  

---

## 🧪 Results Summary

| Logic Style   | Average Power Consumption |
|---------------|----------------------------|
| CMOS          | 17.71 µW                   |
| Pseudo-NMOS   | 5.822 mW                   |

> CMOS offers significantly lower power consumption, while Pseudo-NMOS reduces transistor count but increases static power usage.

---

## 📷 Screenshots

- ✅ CMOS Schematic and Transient Waveform  
- ✅ Pseudo-NMOS Schematic and Transient Waveform  
- ✅ Symbolic hierarchical design  

*(Add screenshots here in your repo for visual reference.)*

---

## 🧾 Tools Used

- 📐 **Cadence Virtuoso** – Schematic Design  
- 📊 **Spectre Simulator** – Transient and Power Analysis  
- 📚 **VLSI Circuit Analysis**

---



## ✅ Conclusion

This project highlights trade-offs between **power efficiency** and **design simplicity** in VLSI circuits. CMOS is better suited for energy-constrained applications, whereas pseudo-NMOS may be ideal where transistor count and simplicity are prioritized.
