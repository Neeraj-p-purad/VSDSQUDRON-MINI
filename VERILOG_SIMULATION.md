# FUNCTIONAL SIMULATION
**For Ubuntu**

 Open your terminal and type the following to install iverilog and GTKWave
 ```
 $   sudo apt get update
 $   sudo apt get install iverilog gtkwave
 ```

![WhatsApp Image 2024-03-02 at 1 03 10 PM](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/f998805f-33ee-4949-a286-b0be5dc924f1)


- **To clone the repository and download the netlist files for simulation, enter the following commands in your terminal.**

 ```
 $ git clone https://github.com/ajeethdani/ajeetkumarkdani
 $ cd Documents
 $ cd hello
```
![WhatsApp Image 2024-03-02 at 1 03 10 PM (1)](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/e03d26cf-b956-4bfa-8d37-f1db4c416bad)


- **To simulate and run the Verilog code, enter the following commands in your terminal.**

```
$ iverilog -o hello hello.v hello_tb.v
$ ./hello
```
![WhatsApp Image 2024-03-02 at 1 03 10 PM (2)](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/7773e5f3-f3a3-40a5-b096-0dfbf1accf2e)



- **To see the output waveform in gtkwave, enter the following commands in your terminal.**

`$ gtkwave hello.vcd`



  Full 5-stage instruction pipeline and pc-increment description Waveform
  
![WhatsApp Image 2024-03-05 at 7 25 19 AM](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/d40f80a3-69e9-40a1-992c-d0d610a4efcf)

![WhatsApp Image 2024-03-05 at 7 27 31 AM](https://github.com/ajeethdani/ajeetkumarkdani/assets/114277218/0d0363cd-e81c-46a2-84c5-69f0d516e989)





