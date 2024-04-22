**Task 4 Execution Overview**

**Follow these steps to view the gtkwave window:**

1. Check the contents of the folder using the command `ls`.
2. Simulate the Verilog code and check for errors using `iverilog neeraj.v neeraj_tb.v`.
3. Execute `./a.out` to generate the output and prepare the VCD file.
4. After running the above commands, execute `gtkwave neeraj.vcd` to open the gtkwave window.

**Verilog Code Overview**

Before proceeding with the execution instructions, let's review some sections of the Verilog code:

1. **Instruction Fetch Stage:**




   !![314470941-4207e62c-8e17-448e-83d1-f6610d4b81dc](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/f53a1a6f-8906-40bb-afde-4e4cae26ac86)

3. **Instruction Decode Stage:**
   ![Instruction Decode Stage]![314471177-80f9a3b7-2e6b-46bb-a285-b0d779b30b19](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/6f2db3a9-9357-4fa0-9413-908327149423)

4. **Hardcoded Instructions:**
   ![Hardcoded Instructions]
   ![314471507-18c150f0-756a-4c30-b850-3fa5f9d101e4](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/f1cae355-e841-437c-8bdc-a376dfbe6748)


**Execution Stage with Waveforms**

1. Upon selecting the instantiated module, all registers and wires are displayed:
   ![Instantiated Module](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/80b939ef-ae09-42ca-b2a8-cab741534af2)

2. By adding signals, waveform representations can be observed:
   ![Waveform Representation](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/a94be91a-e264-4baa-85eb-5806f302de86)

**Output Demonstrating Various Operations**

- **Addition Operation:**
  ![Add Operation Output](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/15e40150-f6aa-4eaa-acc9-bae5b3edd18e)

- **Subtraction Operation:**
  ![Subtraction Operation Output](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/2eca97bb-771d-4bc9-ad2a-d7bdbe0914d9)

- **AND Operation:**
  ![AND Operation Output](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/93598fe0-75e6-4e81-94f8-df1f651d43b5)

- **OR Operation:**
  ![OR Operation Output](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/30e8a69c-ae7c-487e-aea6-d8c3bf386db5)

- **XOR Operation:**
  ![XOR Operation Output](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/e21ef08f-453f-4b99-8895-3ebed15a3007)

