# DAY 3 - LAB EXCERCISES USING TL-VERILOG AND MAKERCHIP
## Introduction to Makerchip platform

    1. Open the link in any browser https://makerchip.com/
    2. Launch the IDE and go through the various functions and windows
    3. To familiarize, toutorial section can help to understand the tool
![image](https://github.com/user-attachments/assets/3ddeac0e-c481-40ae-a0fb-ab55930f7b49)

    4. Can check verilog code
![image](https://github.com/user-attachments/assets/e2737b19-48e8-4db5-95d8-f1cfc5a78d24)


### Basic tutorial with an example:
  ![image](https://github.com/user-attachments/assets/10f55bc6-c14b-4655-9f78-3b52ed32db49)
   
    1. Check the Pipeline FPGA Multiplier to get accustomed with how the tool behaves
    2. If you select any logic in the DIAGRAM section on the right side, we can go and check the highlighted line and if we click on it it will tkae us to the EDITOR section on the left
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/34e95ce8-fe3d-46bb-bc18-ec297b071507" />
    
    3. The editor section of the selected line number 35
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4b96da2d-8c46-405b-bafd-31e0153a783b" />

### Makerchip platform another example with the Pythagorean Example
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a423af4a-88f2-472f-92f2-636c3584ab55" />

    1. CHeck out the basic zoom in/out, panel splitting actions
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d7c949d1-9444-4a9a-9a5e-1ab92cf6762a" />

    2. Select the "bb_sq" logic
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/52331b3f-f2b1-4d25-a1bb-eab5fc9f027f" />




### Combo Logic excercises
#### Inverter
  ![image](https://github.com/user-attachments/assets/489eb2de-df02-43dc-ad99-d597e6358333)
#### Vectors:
  
       1. Bit ranges can generally be assumed on the LHS, but with no assignments to the signals, they have to be programmed explicitly
       2. Example with vector of 5-bits.
![image](https://github.com/user-attachments/assets/6f663f0b-b533-4b80-8f2b-2fd061c16632)

#### MUX
        1. The ternary operation is used for MUX creation 
  ![image](https://github.com/user-attachments/assets/0a1dc35c-d0b6-426e-a5e4-6047fca921b9)

        1. Similar example for MUX to operate on vector
  ![image](https://github.com/user-attachments/assets/9bcf6be1-08d5-4069-b130-fd3ba0259115)

#### Combination Calculator

        1. Implementation of calculator to perform +, -, *, / using two inputs with 32 bit data and 2 bit operational select signal
  ![image](https://github.com/user-attachments/assets/0fa8b7b1-dd62-45b7-b6fa-2e65539b3be4)


  *******GET THIS FIX AFTERWARDS

### Sequential Logic
#### Values in Verilog - move this to theory part

  -> Goal: 
    > zero-extend or truncate when widths are mismatched
    > uses 2-state simulation (no X's)

#### Sequential Calculator

  -> Real calculator remembers the last result and uses it for the next level of calculation, therefore we use a flip-flop
    > Return to the calculator
    > Update calculatort to perform a new calculation each cycle where $val1[31:0] = result of the previopus calculation
    > Reset $out to zero
    > Copy code to local area if required
  ![image](https://github.com/user-attachments/assets/54671c19-9891-45fb-a609-b5ecc5820a5a)


### PIPELINED LOGIC
#### 2-CYCLE CALCULATOR



## DAY 4 - BASIC RISC-VCPU MICROARCHITECTURE
### MIRCO ARCHITECTURE OF SINGLE CYCLE RISC-V CPU
![image](https://github.com/user-attachments/assets/aa988251-c520-470a-b164-2eec4ac9e163)



      
