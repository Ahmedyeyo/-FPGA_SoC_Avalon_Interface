# FPGA SoC Implementation – Custom Soft-Core Processor & Avalon Interconnect  
**Developer:** [Ahmed Abdulkadir]  
**Technologies:** Intel Quartus Prime, Platform Designer, Nios II, C, Avalon Bus  

## 📌 Project Description  
This project demonstrates the design and implementation of an **FPGA-based embedded system** featuring a **soft-core CPU**. The system includes **memory-mapped communication via the Avalon Interconnect**, **JTAG UART communication**, and a fully customized **SoC architecture**.  

## 🔧 Features  
✅ Implemented a soft-core CPU with internal RAM  
✅ Memory-mapped I/O via Avalon Interconnect  
✅ C firmware interacting with FPGA via JTAG  
✅ Hardware architecture implemented using Platform Designer  

## 📂 Repository Structure  
- **hdl_architecture/** – FPGA configurations and Qsys files  
- **embedded_firmware/** – C code and compilation files for the soft-core CPU  
- **hardware_abstraction_layer/** – Drivers and abstraction layer for Avalon Memory-Mapped Interface  
- **documentation/** – Technical reports and analysis  

## 🛠️ Technologies & Tools  
- **FPGA Design:** Quartus Prime, Platform Designer  
- **Embedded Programming:** C, Nios II SBT  
- **Communication:** JTAG UART, Avalon Memory-Mapped Interface  
- **Debugging & Testing:** Eclipse Debugger, SignalTap II  

## 📝 Installation & Usage  
1. Open Quartus Prime and import `FPGA_SoC_Avalon_Interface.qar`  
2. Generate the hardware design using **Platform Designer**  
3. Compile and upload `main.c` via Nios II SBT  
4. Connect via **Nios II Terminal** and verify functionality  

---

