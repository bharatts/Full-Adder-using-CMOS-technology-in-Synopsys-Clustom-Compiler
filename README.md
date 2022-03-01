# Implementation of Full Adder Using 28nm CMOS Technology
Full Adder (One Bit) is designed using 28nm CMOS technology by using Synopsys Custom Compiler


# Table of Content 
- ABSTRACT 
- INTRODUCTION
- TOOLS USED
- FULL ADDER USING CMOS CIRCUIT DESIGN
- NETLIST
- ACKNOWLEDGEMENT 
- REFERENCE 


## ABSTRACT

The one-bit full adder circuit is one of the most widely used building blocks in all digital system and digital signal processing architectures. In the following we will examine the circuit structure and the realization of the full adder using the conventional CMOS design style.

# INTRODUCTION

A Full adder is a combinational circuit that forms the arithmetic sum of three input of one bit. It have three inputs and one output. Two of the variable is denoted by A,B and Cin represent the two significant position. The twp outputs are denoted by symbol S for sum and C for carry out. The truth table of the full adder is

![image](https://github.com/bharatts/Full-Adder-using-CMOS-technology-in-Synopsys-Clustom-Compiler/blob/main/images/Truth%20Table%20of%20Full%20Adder.jpg)

The sum and carry out of the signals of the full adder are defined as the following of two Boolean functions of the three input variables A,B and C.

![image](https://github.com/bharatts/Full-Adder-using-CMOS-technology-in-Synopsys-Clustom-Compiler/blob/main/images/CMOS_Full_Adder_Boolean_equation.jpg)

Gate-level schematic of the one bit full-adder circuit is shown below

![image](https://github.com/bharatts/Full-Adder-using-CMOS-technology-in-Synopsys-Clustom-Compiler/blob/main/images/FullAdder.jpg)

The transistor-level desing of the CMOS full-adder ciruit is shown below It noted that the circuit contains a total of 14 NMOS and 14 PMOS transistors, with the two CMOS inverters which are used to generate the outputs.

![image](https://github.com/bharatts/Full-Adder-using-CMOS-technology-in-Synopsys-Clustom-Compiler/blob/main/images/transistor%20level%20diagram%20full%20adder.jpg)

# TOOL USED

- Synopsys Custom Compiler:  The Synopsys Custom Compiler™ design environment is a modern solution for full-custom analog, custom digital, and mixed-signal IC design. As the heart of the Synopsys Custom Design Platform, Custom Compiler provides design entry, simulation management and analysis, and custom layout editing features. This tool was used to design the circuit on a transistor level.

- Synopsys Primewave:  PrimeWave™ Design Environment is a comprehensive and flexible environment for simulation setup and analysis of analog, RF, mixed-signal design, custom-digital and memory designs within the Synopsys Custom Design Platform. This tool helped in various types of simulations of the above designed circuit.

- Synopsys 28nm PDK:  The Synopsys 28nm Process Design Kit(PDK) was used in creation and simulation of the above designed circuit.

# Full Adder Using CMOS CIRCUIT DESIGN

The CMOS design for Full Adder schematic is shown in fig. 

- SCHEMATIC

![image](https://github.com/bharatts/Full-Adder-using-CMOS-technology-in-Synopsys-Clustom-Compiler/blob/main/images/CMOS_Full_Adder_Schematic.jpg)

- SYMBOL

![image](https://github.com/bharatts/Full-Adder-using-CMOS-technology-in-Synopsys-Clustom-Compiler/blob/main/images/CMOS_Full_Adder_Symbol.jpg)

                                                                                                                                                                                
 - Testbench Symbol                                                                                                                                                                           


![image](https://github.com/bharatts/Full-Adder-using-CMOS-technology-in-Synopsys-Clustom-Compiler/blob/main/images/CMOS_Full_Adder_Schematic_Testbench.jpg)                                                                                                                                                                                                                                                                                                                                                                               
- PRIMEWAVE WINDOW


![image](https://github.com/bharatts/Full-Adder-using-CMOS-technology-in-Synopsys-Clustom-Compiler/blob/main/images/CMOS_Full_Adder_Schematic_Testsuite.jpg)                                                                                                                                                                                                                                                                                                                                                                                          - TESTBENCH WAVEFORM                                                                                     


![image](https://github.com/bharatts/Full-Adder-using-CMOS-technology-in-Synopsys-Clustom-Compiler/blob/main/images/CMOS_Full_Adder_Schematic_Waveform2.jpg)                                                                                                                                                                                                                                                                                                                                                                                                    

# NETLIST
The netlist of the above circuit has also been uploaded to the github repo with the file name - Netlist.txt 

# AUTHOR
Bharat Suthar, MTech VLSI and Embedded Systems , Defence Institute of Advanced Technology, Pune, Maharashtra

# ACKNOWLEDGEMENT 

- Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd.
- Synopsys, India
- VLSI System Design(VSD) Corporation Private Limited India
- Indian Institute of Technology, Hyderabad 
- Cloud Based Analog IC Design Hackathon
- Sameer Durgoji, NIT Karnataka
- Chinmay panda, IIT Hyderabad

# REFERENCES

- CMOS Digital Integrated Circuit Analysis and Design Sung-Mo Kang and Yusuf Leblebici
- J. M. Rabaey, A. Chandrakasan, B. Nikolic, “Digital Integrated Circuits A Design Perspective”, 2nd Prentice Hall, Englewood Cliffs, NJ, 2002-  Design and Implementation of 15-   4 compressor Using 1 – bit Semi Domino Full Adder at 28nm Technology, G.RAJU, S.Aruna, G.Ranjith Kumar, S.Vasu Krishna
- Implementation of Carry Select Adder Using CMOS Full Adder, SmitsShree.Mohapatra, R. VaibhavKumar
