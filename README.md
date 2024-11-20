
# **Hardware Projects Repository**

### **Overview**  
This repository showcases a collection of my hardware-focused projects, implemented in Verilog and designed to explore digital logic, memory systems, and control mechanisms. These projects demonstrate advanced concepts like modular design, state machines, and memory management, combining theoretical principles with practical applications.

---

### **Projects Included**

1. **Simon Game Implementation**  
   - A modular Verilog implementation of the classic memory-based Simon game.
   - Features a **datapath** for pattern storage, playback, and validation, and a **control unit** for state transitions.
   - Includes a comprehensive testbench for simulation and validation of game functionality.

2. **Stoplight Controller**  
   - A finite state machine (FSM) that controls traffic lights at an intersection.
   - Implements timed transitions between green, yellow, and red lights for two roads, factoring in car presence.
   - Validated using testbenches to simulate real-world scenarios.

3. **SR Latch and Memory Block**  
   - Implements basic SR latches and a hierarchical memory block using sequential logic.
   - Demonstrates state-holding circuits and their role in larger memory systems.
   - Includes testbenches to validate functionality under various input conditions.

---

### **Features**
- **Modular Design**: All projects are built using reusable and scalable Verilog modules.
- **State Machine Implementation**: Projects like the stoplight controller utilize FSMs to manage complex behaviors.
- **Testbenches for Validation**: Each project includes a testbench to simulate and verify correctness.
- **Practical Applications**: Projects are designed to bridge theoretical knowledge with real-world hardware challenges.

---

### **How to Use**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hardware-projects.git
   cd hardware-projects
   ```
2. Open the Verilog files in a simulator (e.g., ModelSim, Vivado, or Icarus Verilog).
3. Run the provided testbenches to simulate and validate the designs:
   ```bash
   iverilog -o testbench_output <project_name_testbench>.v <dependent_modules>.v
   vvp testbench_output
   ```
4. For FPGA implementation, synthesize the top-level module and load it onto the hardware.

---

### **Tools Used**
- Verilog HDL
- Vivado

---

### **Contact**
📫 Reach out via **[vd4689@princeton.edu](mailto:vd4689@princeton.edu)** or connect on **[LinkedIn](https://www.linkedin.com/in/venusdinari/)**.  

Feel free to explore the projects and contribute your ideas or suggestions!
