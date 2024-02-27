**By Referring to C-based Lab videos and RISC-V-based lab videos**

**Snapshots of the compiled C code and RISC-V**

**Step 1: check whether the leafpad is installed in ur machine by using the commands
leafpad sum1ton.c& (sum1ton.c is the file name)
If the leafpad editor is opened without any errors then type the C code.**
****If the leafpad is not installed in ur machine then install by using the following command**

**sudo snap install leafpad****
![1](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/93af17aa-df22-452d-8a24-68f2aca95b52)

****Step 2: Writing the C code in the leafpad editor** using the following command
![2](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/04bb51bb-1d2c-4784-bf04-66f68b0790d0)

**leafpad sum1ton.c&**

**Step 3: After writing the C code save the editor by Ctrl+s**

**Step 4: Check for the errors by using the following command(compilation step)**

**Step 5: Check the output by using the command**

**./a.out**
![3](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/a8cba041-b362-45cc-9f22-1d429ec78d14)

**The results will be displayed as** 

**Sum of numbers from 1 to 500 is 125250**


********************************************************RISCV Compilation and Execution*****************************************************

**Step 1: View the C Code in the editor window using the following command**

**cat sum1ton.c**
![x](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/301d86fd-3e34-445b-a90f-52bc5928fa27)

**Step 2: Compile the code in riscv using the following command**

**riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**
![5](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/ac7a88b3-c774-4a30-a8a7-f7fec040d155)

**Step 3: The ls ltr command in Linux is used to list the contents of the current directory in long format, sorted by last modified time in reverse order.**

**use the command**

**ls -ltr sum1ton.c**

![5](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/ff7db1ad-8d3f-46eb-9098-6b94151448cb)


**Search for the Main and check the instructions of the C code execution. It has 15 instructions in the C execution**

![6](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/13a25b0c-6f6d-4353-92e6-b8d987090e07)


**Step 4:**

**riscv64-unknown-elf-gcc -Ofast -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**


![7](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/723a6153-ec18-48cd-8b83-6bd8e46db459)


![8](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/b6a01e2b-b238-41a8-891a-20816c82720d)


![9](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/af13184e-8928-4889-9565-3d683f0f7c6b)



