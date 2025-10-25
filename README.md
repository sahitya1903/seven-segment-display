## 🔢 Seven Segment Display on FPGA 
- A simple **Verilog project** demonstrating how to drive a **seven-segment display** using **Xilinx Vivado**.  
- This project includes HDL source files and FPGA constraint mapping for implementation and testing.
- This project displays hexadecimal digits (0–9, A–F) on a **7-segment display** by decoding binary input into segment control signals.  
- It’s designed to run on **Xilinx Spartan-7** or compatible FPGA boards.

---

## 📁 File Structure
```bash
seven-segment-display/
│
├── seven_segment.srcs/
│   ├── constrs_1/new/sevenseg_fpga.xdc      # FPGA pin constraints
│   └── sources_1/new/sevenseg.v             # Verilog source file
│
├── seven_segment.xpr                        # Vivado project file
│
├── README.md                                # Project overview and setup guide
└── LICENSE                                  # Open-source license (MIT)
```

---

## ⚙️ How to Run
1. Open **Vivado**.
2. Click **File → Open Project** and select `seven_segment.xpr`.
3. Synthesize, implement, and generate the bitstream.
4. Connect your FPGA board and program it with the generated bit file.
5. Observe the seven-segment display output!

---

## 🧰 Tools Used
- Vivado 2023.x or later
- Verilog HDL
- Xilinx Spartan-7 FPGA Board

## 📜 License
This project is open source under the MIT License.

## 💡 Author
Developed by **Sahitya Kushwaha** — FPGA & Digital Design Enthusiast 💫
