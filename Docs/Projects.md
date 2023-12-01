# PROJECTS

## MIPS processor verification using UVM [ [link] ](https://github.com/cp024s/MIPS-Processor-Verification-UVM)

1. **Objective:** Verify the MIPS processor design using Universal Verification Methodology (UVM).

2. **Methodology:** Employ UVM to establish a standardized verification environment.

3. **Components:** Develop UVM testbenches, incorporating functional coverage and constrained-random stimulus generation.

4. **Validation:** Conduct extensive simulations to validate the MIPS processor's functionality and adherence to architectural specifications.

5. **Outcome:** Enhance the reliability and robustness of the MIPS processor, ensuring seamless integration into diverse computing systems.


## 5 stage pipelined architecture in RISC (on progress) [ [link] ](https://github.com/cp024s/5-Stage-Pipelined-Architecture)

1. **Objective:** Design and implement a 5-Stage Pipelined Architecture for a processor, aiming to enhance instruction throughput and overall system performance.

2. **Pipeline Stages:** Establish distinct pipeline stages, including Instruction Fetch (IF), Instruction Decode (ID), Execute (EX), Memory Access (MEM), and Write-Back (WB), enabling concurrent execution of multiple instructions.

3. **Instruction Set Adherence:** Ensure the processor's compatibility with a specified instruction set through rigorous testing, verifying correct execution and proper handling of data transfers across the pipeline stages.

4. **Pipelined Operation Verification:** Conduct experiments to validate the efficient operation of the pipelined architecture, assessing the flow of instructions through each stage and optimizing the pipeline for improved instruction throughput.

5. **Hazard Handling and Forwarding:** Implement and test hazard mitigation strategies, including data hazards, control hazards, and structural hazards. Verify the effectiveness of forwarding mechanisms to maintain pipeline efficiency.

6. **Performance Analysis:** Evaluate the overall performance of the 5-Stage Pipelined Architecture, considering factors such as throughput, latency, and resource utilization. Optimize the design to achieve enhanced computational efficiency in diverse computing scenarios.

## 1x3 Router design [ [link] ](https://github.com/cp024s/1x3-Router)

1. **Router Architecture and Design:** Develop a concise and efficient 1x3 router architecture using Verilog, outlining the structure of input and output ports and the logic for data packet routing.

2. **Verilog Implementation:** Code the router's functionality in Verilog, translating the architectural design into executable hardware description language that accurately represents the desired behavior of the 1x3 router.

3. **Testing and Validation:** Create a comprehensive testbench to validate the router's performance under various conditions, ensuring correct packet routing, error handling, and proper functioning of the implemented design.

4. **Performance Analysis:** Conduct thorough performance analysis, evaluating the router's throughput, latency, and efficiency. Optimize the design to enhance these metrics, addressing any identified bottlenecks or areas for improvement.


## Protocol Verification projects 

1. **AXI Stream:** [ [link] ](https://github.com/cp024s/AXI-stream) <br>
   Conducting verification experiments for AXI Stream communication protocol, validating its compliance with industry standards. The experiments include rigorous testing of data streaming, handshaking, and protocol-specific features to ensure reliable and efficient communication within digital systems.
   
3. **AHB to APB BRIDGE:** [ [link] ](https://github.com/cp024s/AHB-APB-bridge) <br>
   The AHB to APB bridge is a crucial component in embedded systems, seamlessly connecting the high-performance Advanced High-Performance Bus (AHB) with the more peripheral-oriented Advanced Peripheral Bus (APB).
   Serving as a translator, it efficiently manages data transfer between these buses, optimizing communication between core processors and peripheral devices.
   This bridge ensures a smooth and synchronized flow of data, enhancing overall system performance and allowing for streamlined integration of diverse hardware components.
   Its role is pivotal in maintaining a balanced and efficient data exchange within complex embedded systems.
   
5. **PCIe:**
   Verifying the PCIe communication protocol through systematic experiments, assessing its functional correctness and performance characteristics. The experiments focus on link initialization, data transfer, and protocol-specific functionalities, ensuring PCIe compliance and optimizing its performance in diverse computing environments.

6. **UART:** [ [link] ](https://github.com/cp024s/AXI-stream) <br>
   Performing verification experiments for UART communication protocol, ensuring accurate and reliable serial communication. The experiments cover baud rate settings, start/stop bit handling, and error detection mechanisms, validating the protocol's robustness and compatibility for asynchronous data transmission.

7. **AMBA:**
   Conducting comprehensive verification experiments for the AMBA communication protocol, encompassing AHB and APB bus architectures. The experiments focus on verifying proper data transfer, bus arbitration, and protocol compliance, ensuring seamless integration and communication between AMBA-compliant components.

8. **RS 232:** [ [link] ](https://github.com/cp024s/RS-232) <br>
   Verifying the RS 232 communication protocol through targeted experiments, assessing its ability to facilitate serial communication. The experiments cover voltage levels, baud rate configurations, and error handling mechanisms, ensuring the protocol's reliability and suitability for asynchronous serial communication applications.


## Single Cycle RISC Implementation [ [link] ](https://github.com/cp024s/Single-cycle-RISC)

1. **Objective:** Implement a Single-Cycle RISC processor adhering to RISC architecture principles.
  
2. **Design and Implementation:** Develop a processor architecture where each instruction completes within a single clock cycle, simplifying the control unit and ensuring uniform execution time for all instructions.

3. **Instruction Set Compliance:** Verify the processor's adherence to a specified instruction set through systematic tests, validating the correct execution and proper handling of data transfers between registers and memory.

4. **Data Path and Control Unit Validation:** Conduct experiments to validate the proper functioning of the processor's data path and control unit. This includes testing the accurate execution of arithmetic and logic operations, as well as the coordination between the control unit and other components in the processor.

5. **Memory Access and Addressing Verification:** Perform tests to ensure precise memory access and proper handling of various addressing modes, confirming the correct implementation of data loading and storing operations.

6. **Hazard Handling and Forwarding:** Verify the processor's ability to handle hazards, such as data, control, and structural hazards, and assess the effectiveness of forwarding mechanisms to enhance performance.
