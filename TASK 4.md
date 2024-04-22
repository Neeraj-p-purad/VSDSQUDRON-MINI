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
   ![Instruction Decode Stage]


   ![314471177-80f9a3b7-2e6b-46bb-a285-b0d779b30b19](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/6f2db3a9-9357-4fa0-9413-908327149423)

5. **Hardcoded Instructions:**
   ![Hardcoded Instructions]


   ![314471507-18c150f0-756a-4c30-b850-3fa5f9d101e4](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/f1cae355-e841-437c-8bdc-a376dfbe6748)


**Execution Stage with Waveforms**

1. Upon selecting the instantiated module, all registers and wires are displayed:
   ![Instantiated Module]![WhatsApp Image 2024-04-22 at 11 37 30_f3769490](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/a44436b5-e73f-4501-bbeb-25ac3914fc25)


2. By adding signals, waveform representations can be observed:
   ![Waveform Representation]![WhatsApp Image 2024-04-22 at 12 09 45_c0829e6e](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/1058ef59-c29f-4ae0-8167-00538217d900)


**Output Demonstrating Various Operations**

- **Addition Operation:**
  ![WhatsApp Image 2024-04-22 at 12 23 00_d9d9fe69](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/14f26c62-48f9-4b04-b310-dd606e2bc89d)

- **Subtraction Operation:**
  ![Subtraction Operation Output]![WhatsApp Image 2024-04-22 at 12 24 22_2008d650](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/540efbf7-1b3f-4399-9216-3f335a54139b)

- **And Operation:**
  ![ And Operation Output] ![WhatsApp Image 2024-04-22 at 12 26 57_63789c92](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/e3d514d6-e5be-42e8-b07e-9e5bc778f1d3)

- **OR Operation:**
 ![OR Operation Output]![WhatsApp Image 2024-04-22 at 12 27 48_8859a99b](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/734adf26-a112-4d1f-be15-5833c44d7257)


- **XOR Operation:**
  ![XOR Operation Output](![WhatsApp Image 2024-04-22 at 12 28 42_7b61ebfe](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/658ff0cf-7061-4119-991f-e3bef38593d9)
