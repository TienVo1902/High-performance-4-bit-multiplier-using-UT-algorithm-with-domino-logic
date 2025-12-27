# High Performance 4-Bit Multiplier using UT Algorithm with Domino Logic

## 📖 Introduction
This project focuses on the design and simulation of a **High-Performance 4-Bit Multiplier** utilizing the **Urdhva Tiryagbhyam (UT) Algorithm** combined with **Domino Logic** techniques. The design aims to optimize calculation speed and compares the performance against traditional Static CMOS logic.

This research was conducted as part of the **VLSI Circuits Design** course at **Ho Chi Minh City University of Technology and Education (HCMUTE)**.

## 🚀 Key Features
-   **Algorithm:** Urdhva Tiryagbhyam (Vedic Mathematics) for "Vertically and Crosswise" multiplication.
-   **Logic Family:**
    -   **Static CMOS:** Baseline design for comparison.
    -   **Domino Logic:** High-speed dynamic logic technique implementing Precharge and Evaluation phases.
-   **Components Designed:** Logic Gates (NOT, AND, OR, XOR...), Half/Full Adders, 4-bit RCA, and 4x4 Multipliers.

## 🛠 Tools Used
-   **Design & Simulation:** Cadence Virtuoso.
-   **Environment:** VMware Workstation.
-   **Analysis:** Microsoft Excel (for delay/power calculation).

## 📂 Repository Structure
The source code is organized into two main archives corresponding to the logic families simulated:

-   📁 **`Static_CMOS.rar`**: Contains schematic and simulation files for the multiplier using standard Static CMOS logic.
-   📁 **`Domino_CMOS.rar`**: Contains schematic and simulation files for the multiplier using Domino Logic (High-speed variant).

## 📊 Performance Comparison
The project compares the two designs based on Delay and Power Consumption.

| Metric | Static CMOS | Domino Logic | Improvement/Trade-off |
| :--- | :--- | :--- | :--- |
| **Delay** | Slower | **27% Faster** | Domino Logic significantly reduces delay. |
| **Static Power** | Lower | **+4% Higher** | Domino consumes slightly more leakage power. |
| **Dynamic Power** | Lower | **+21% Higher** | The high-speed switching of Domino logic increases dynamic power consumption. |

**Conclusion:** Domino Logic is superior for high-speed applications (27% faster) but requires a trade-off in power consumption compared to Static CMOS.

## 📜 References
1.  N. L. Reddy et al., "Design of a high performance 4 bit multiplier using UT algorithm with domino logic," IEMCON 2016.
2.  Project Report: *High Performance 4 Bit Multiplier Using UT Algorithm With Domino Logic*, HCMUTE, Jan 2025.
