# FUNCTIONAL SIMULATION
**For Ubuntu**

 Open your terminal and type the following to install iverilog and GTKWave
 ```
 $   sudo apt get update
 $   sudo apt get install iverilog gtkwave
 ```

![neeraj2](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/f2ce1528-41c4-4639-9854-4aafba608d54)



- **To clone the repository and download the netlist files for simulation, enter the following commands in your terminal.**

 ```
 $ git clone https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI
 $ cd Documents
 $ cd hello
```

![neeraj2](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/f2ce1528-41c4-4639-9854-4aafba608d54)

- **To simulate and run the Verilog code, enter the following commands in your terminal.**

```
$ iverilog -o hello hello.v hello_tb.v
$ ./hello
```





- **To see the output waveform in gtkwave, enter the following commands in your terminal.**

`$ gtkwave hello.vcd`



  Full 5-stage instruction pipeline and pc-increment description Waveform

![neeraj3](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/8829dc08-7144-4cc1-aa08-afc4ec3ae425)

![neeraj4](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/1859608f-6301-429a-9095-b7d15b7501f6)




