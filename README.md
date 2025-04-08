# RISC-V_MYTH
## RV D3 - Digital Logic with TL-Verilog and Makerchip
### R-D2SK1 - Combinational logic in TL-Verilog using Makerchip
#### Logic Gates
![image](https://github.com/user-attachments/assets/87a26a32-b523-4458-b186-d0e5107110cf)
#### Combo Circuit
![image](https://github.com/user-attachments/assets/d68ebd0a-3aa0-4cd6-b668-275ea7ca173e)
     1. Represents a full adder circuit
     2. Use to compose into larger adder circuits like below
     ![image](https://github.com/user-attachments/assets/a41b6031-072d-47ae-b2bc-2d217d77d30f)
#### Boolean Operators
![image](https://github.com/user-attachments/assets/caf8d861-14b7-4962-8d0e-a25358c76f63)

### RV-D3SK1_L2 MUX Implementation and Intro to Makerchip
#### MUX
![image](https://github.com/user-attachments/assets/806d839d-fc71-46fd-a12b-69de75286fe2)

#### Chaining Ternary operator
![image](https://github.com/user-attachments/assets/2016559c-8444-4055-a9d2-d6d8245276df)
    -> select rightmost has the first priority
    -> Assign without parenthesis, so the highest priority first

#### Maker Chip


## RV D4 - Basic RISC-V CPU Micro-architecture
### Intro to Simple RISC-V Micro-acrchitecture

#### Single Cycle RISC-V CPU
![image](https://github.com/user-attachments/assets/3fd780d4-7c57-4003-9094-65ac3eca9703)
     
     1. R` is the intruct set acritect and not the mirco arch that is implementing thje instruction set
     2. First the Program Counter is sent to the intruction memory and the output is instruction comes as output
     The Decode logic is breeak down the source, denst reg and some inst like branch might have immediate value. The branch has an offset value to the PC. And this is goin to the target instruction. The adder is computing the nest PC for brancgh with the offset value and becomes the new PC
     4. Most instruction are aritechmetic and operation oif source reg. Arrary or mems access one value at time, incase of CPU, need to access 2 source reg at a time
     5. 2 reg oput put values now will be operated by the ALU as per the compuitatioh( codded as per the previous caluclator wjhoch has memeory from the computations
     6. The RF write than writes the value from the ALU, which is actually one unit with the RF read
     7. DMem is a memory which will hold tghe data  from the offset and the address will be created in it for the data to be stored
     

