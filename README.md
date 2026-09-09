# ⚙️ EDITED YEAR 1 — HARDWARE ENGINEERING (hardware-mastery-year01)

[M1-M4] Nand2Tetris Stack ──> [M5-M6] Physical Circuitry ──> [M7-M8] Robotics & CAD ──> [M9-M10] FRC Industrial & PCBs ──> [M11-M12] Diagnostics & IT
(Logic Gates up to OS) (Arduino & I/O Sensors) (Motors & Fusion 360) (High Power & KiCad) (Refurbishing & Soldering)


## 🛠️ Months 1–4 — The Nand2Tetris Mastery Phase
**Mission:** Build a complete 16-bit computer from raw NAND gates all the way up to an operational, high-level computer system to master the hardware-software interface.

### Months 1–2 — Hardware Foundations (Part I)
*   **Primary work:** Build fundamental gates (AND, OR, XOR), design an ALU, construct RAM/Registers, wire the custom Hack CPU, and write a low-level machine language assembler.
*   **GitHub Output:** Validated Hardware Description Language (`.hdl`) files and functional assembly code.

### Months 3–4 — Software Abstractions (Part II)
*   **Primary work:** Write a Virtual Machine stack translator, build a full compiler (tokenization/parsing) for the Jack language, and code core OS libraries.
*   **Final Pipeline Artifact:** A complete Jack → VM → Assembly → Hack Machine compilation chain.
*   **Gate:** Explain and visually trace a high-level line of code down to physical ALU state manipulation.

---

## 🔋 Months 5–6 — Physical Circuitry & I/O
**Mission:** Cross the boundary from software simulations to real-world physical electricity.

### Month 5 — Electronics Fundamentals
*   **Learn:** Voltage, current, resistance, Ohm’s Law, digital vs. analog signals, and GPIO architectures using an **Arduino Starter Kit** and a digital multimeter.

### Month 6 — Sensors & Communication
*   **Learn:** Sensor monitoring (ultrasonic, temperature, light), PWM, and wire-level communication protocols (**UART, I²C, SPI**).
*   **Gate:** Understand *why* a protocol signal functions at the electrical level, rather than just relying on pre-built software libraries.

---

## 🤖 Months 7–8 — Robotics + Actuators + CAD
**Mission:** Force computational logic to physically move physical objects.

### Month 7 — Motors & Mechanical Engineering
*   **Learn:** Precise locomotion using servo, stepper, and DC motors (via H-bridge drivers). Learn computer-aided design (**Onshape**) to build assemblies with calculated tolerances.

### Month 8 — Raspberry Pi Integration
*   **Learn:** Linux-based Single Board Computers, Python GPIO automation, and cross-device MCU ↔ Pi serial communications.

---

## ⚡ Months 9–10 — FRC Industrial Hardware + Custom PCB
**Mission:** Scale up to heavy-duty industrial environments and manufactured electronics.

### Month 9 — Industrial Electrical Systems
*   **Learn:** High-current FRC-style robotics architecture (relays, fuses, wiring standards, 12V power distribution hubs, and automated pneumatic air systems).

### Month 10 — KiCad PCB Design & WPILib
*   **Learn:** Schematics, footprints, trace routing, and Gerber manufacturing via **KiCad**. Integrate hardware directly into the industry-standard WPILib robotics software framework.

---

## 🔧 Months 11–12 — Troubleshooting + Deep IT
**Mission:** Develop the systematic diagnostics framework required to trace and repair complex field failures.

### Month 11 — Hardware Diagnostics & Soldering
*   **Learn:** Multimeter continuity tracing, board-level fault isolation, through-hole soldering, and desoldering component repair.

### Month 12 — Networking & OS Deployment
*   **Learn:** Linux systems networking (DHCP, DNS, SSH) and set up a custom local PXE network boot environment designed to automatically image computers.
