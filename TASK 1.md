# VSDSQUDRON-MINI
# A 4-week Research Internship on RISC-V using VSDSquadron Mini RISC-V Dev Board

[Click here for board link](https://www.vlsisystemdesign.com/vsdsquadronmini/)
## Board Specifications
- **Processor:** CH32V003F4U6 chip with 32-bit RISC-V core based on RV32EC instruction set
- **SRAM:** 2kb onchip volatile sram, 16kb external program memory
- **Processor Speed:** 24 MHz
- **I/O Voltage:** 3.3 V
- **Input Voltage (nominal):** 5 V
- **Sink Current per I/O Pin:** 8 mA
- **Source Current per I/O Pin:** 8 mA
- **Programmer/Debugger:** Onboard RISC-V programmer/debugger, USB to TTL serial port support
- **SPI:** 1x (PC5(SCK), PC1(NSS), PC6(MOSI), PC7(MISO))
- **I2C:** 1x (PC1(SDA), PC2(SCL))
- **USART:** 1x (PD6(RX), PD5(TX))
- **External Interrupts:** 8 external interrupt edge detectors, mapped to 18 I/O ports
- **PWM Pins:** 14
- **Analog I/O Pins:** 10-bit ADC (PD0-PD7, PA1, PA2, PC4)
- **Digital I/O Pins:** 15
- **Built-in LED Pin:** 1x onboard user LED (PD6)
- **USB 2.0 Type-C**




BThis repo is intended to document the weekly progress.

### The first online meet was held on 16th of Feb 2024 @6PM

<details>
    <summary> TASK 1 </summary>

1) install RISC-V GNU Toolchain 

2) install Yosys 

3) install iverilog 

4) install gtkwave

### CLONING RISC-V GNU TOOLCHAIN
```sudo apt install git-all```   # To install git

```sudo apt-get install autoconf automake autotools-dev curl python3 libmpc-dev libmpfr-dev libgmp-dev gawk build-essential bison flex texinfo gperf libtool patchutils bc zlib1g-dev libexpat-dev``` *![IMG-20240220-WA0042](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/bb38be13-ca5c-4292-891f-dac75f8a252b)
make sure to install the dependencies*

```git clone https://github.com/riscv/riscv-gnu-toolchain```

## Create a opt dir
```mkdir /opt/riscv```  *try sudo incase of permission denial*

In my case I created a driectory ```mkdir riscv``` and ``` chmod 777 home/nawras/riscv ```

## Config and make inside the risc-v gnu toolchain dir 

```./configure --prefix=/opt/riscv``` 

### INSTALLING IVERILOG GTKWAVE & YOSYS

### YOSYS
```bash
git clone https://github.com/YosysHQ/yosys.git
cd yosys 
sudo apt-get install build-essential clang bison flex \libreadline-dev gawk tcl-dev libffi-dev git \ graphviz xdot pkg-config python3 libboost-system-dev\libboost-python-dev libboost-filesystem-dev zlib1g-dev
make config-gcc
make 
sudo make install
```


![IMG-20240220-WA0044](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/069c21af-a1bd-4e24-9ba7-1fcaa6aef32c)


![IMG-20240220-WA0043](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/facfe404-3fb1-4da7-a5f6-6a5fe6885328)

### iVerilog

```
sudo apt-get install iverilog
```
![IMG-20240220-WA0046](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/ba879034-29f9-4a7d-ac9a-b7c4363e5dcd)

### GTkWave
``` sudo apt-get install gtkwave ```


![IMG-20240220-WA0046](https://github.com/Neeraj-p-purad/VSDSQUDRON-MINI/assets/160604281/a4e0e52b-1f4a-40a4-b7a9-d637e70b29bf)





