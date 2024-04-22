### C-Based Lab

1. **Verify Leafpad Installation:**  
   - Check Leafpad installation:
     ```bash
     leafpad sum1ton.c&
     ```
   - If Leafpad is not installed, install it:
     ```bash
     sudo snap install leafpad
     ```
   ![Leafpad Installation](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/93af17aa-df22-452d-8a24-68f2aca95b52)

2. **Write C Code:**  
   - Open Leafpad and write the C code:
     ```bash
     leafpad sum1ton.c&
     ```
   ![Leafpad Editor](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/04bb51bb-1d2c-4784-bf04-66f68b0790d0)

3. **Save and Compile:**  
   - Save the C code and compile:
     ```bash
     gcc -o sum1ton sum1ton.c
     ```

4. **Execute:**  
   - Run the compiled program:
     ```bash
     ./sum1ton
     ```
   ![Output](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/a8cba041-b362-45cc-9f22-1d429ec78d14)

---

### RISC-V-Based Lab

1. **View C Code:**  
   - Display the C code:
     ```bash
     cat sum1ton.c
     ```
   ![C Code](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/301d86fd-3e34-445b-a90f-52bc5928fa27)

2. **Compile for RISC-V:**  
   - Compile for RISC-V architecture:
     ```bash
     riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c
     ```
   ![RISC-V Compilation](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/ac7a88b3-c774-4a30-a8a7-f7fec040d155)

3. **List Contents:**  
   - Check the file contents:
     ```bash
     ls -ltr sum1ton.c
     ```
   ![File Contents](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/ff7db1ad-8d3f-46eb-9098-6b94151448cb)

4. **Optimize Compilation:**  
   - Recompile with optimization:
     ```bash
     riscv64-unknown-elf-gcc -Ofast -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c
     ```
   ![Optimized Compilation](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/723a6153-ec18-48cd-8b83-6bd8e46db459)
