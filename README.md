# Non-Inverting-Amplifier
This repository contains the complete project files for designing and laying out a Non-Inverting Amplifier circuit PCB using KiCad.

# 📋 Project Overview

This project focuses on creating a simple operational amplifier (op-amp) based non-inverting amplifier circuit, designing the schematic, and developing a ready-for-manufacturing PCB.
It's perfect for beginners and electronics enthusiasts learning PCB design workflows with KiCad.

# 🛠️ Tools Used

   KiCad (Version 7.x recommended)

   Basic understanding of operational amplifiers and PCB design principles.
   
# 📂 Repository Structure

| File/Folder | Purpose |
|:-----------|:--------|
| `NonInvertingAmp.pro` | Main KiCad project file that links everything together. |
| `NonInvertingAmp.sch` | KiCad schematic file containing the amplifier circuit diagram. |
| `NonInvertingAmp.kicad_pcb` | PCB layout file for the circuit (component placement, routing, etc.). |

---

## 🧩 Circuit Description

The **non-inverting amplifier** circuit configuration provides a **positive voltage gain** without inverting the input signal.  
It uses a standard operational amplifier (e.g., **LM741**, **TL081**, or similar) and a pair of resistors to set the gain.

The gain formula:

\[
Gain = 1 + \left( \frac{R_f}{R_{in}} \right)
\]

where:  
- \( R_f \) = feedback resistor  
- \( R_{in} \) = input resistor

---

## 🚀 How to Use

1. Clone or download the repository.
2. Open `NonInvertingAmplifier.pro` in KiCad.
3. Explore the schematic (`.sch`) to understand and modify the design if needed.
4. Open the PCB layout (`.kicad_pcb`) to view or edit the board.
5. Use KiCad's **Plot** tool to regenerate Gerber files if you make changes.
6. Order your PCB using the `gerber/` files!

---

## 📸 Previews

![Screenshot 2025-04-26 192105](https://github.com/user-attachments/assets/b98c400f-8518-440f-89f1-ae6370671bc3)

![Screenshot 2025-04-26 200042](https://github.com/user-attachments/assets/6695c51a-989b-4e33-a285-bfc938a9790d)

![Screenshot 2025-04-26 200123](https://github.com/user-attachments/assets/8266c7c0-1b3e-442e-946c-048d88b1f265)

![Screenshot 2025-04-26 200130](https://github.com/user-attachments/assets/f91cdab6-3384-4706-8fed-87a13aec0242)



