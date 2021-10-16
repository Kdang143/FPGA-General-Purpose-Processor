# FPGA-General-Purpose-Processor

## **Latches, Decoder, and FSM**

The important components that will be used throughout the 3 scenarios are the latches, 4:16 decoder
and the finite machines. The latches are going to be the important building blocks of memory and there
for will play a vital role of storing the last 4 digits of the student ID. In this case latch 1 will store student
digits (60) and latch 2 will store the last 2 digits (16). The 4:16 decoders task will be receiving the signal
of the current sates from the finite-state machine and will decode it to its operation-selector microcode.
The finite-state machine that will be used in this lab for every part is the moore machine since its
simplicity comes from the fact that its outputs will be determined by the current states.

![image](https://user-images.githubusercontent.com/68084112/137590301-1e6dc25a-eafb-4512-aa3d-70978cc505cc.png)


## **Latches, Decoder, and FSM Waveform**

![image](https://user-images.githubusercontent.com/68084112/137590117-eaec867a-9a59-461b-af5b-849f3274069c.png)

## **Complete ALU Circuit Diagram**

The purpose of problem is to procure input data and then represent them in the output of operations of
the ALU. A set of two 8-bit inputs, A and B, will contain the numbers 60 and 16. These numbers will
come from the last four digits of the student ID which means that A = (60) and B = (16) will translate
into binary output. To make sure that the ALU can continue to perform its arithmetical and logical
functions, the two 8-bit inputs will be stored in the latches that will be one of the primary inputs for 
ALU.

![image](https://user-images.githubusercontent.com/68084112/137590264-168e0985-0d6d-4f3b-9597-91cfc68f1be1.png)
