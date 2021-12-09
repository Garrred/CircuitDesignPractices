# CPU Architecture


## Turing Complete
### _This is the final circuit. Scroll down to see the structure of light blue components used in it._

A processing unit that can execute instructions.  

Functionalities:  
Read instruction from memory and execute them.  
Can store values and read from input && write to output.  
Can perform OR AND, NOR, AND, addition, subtraction.  
Dudge if condition is met to perform Jump.
Can transfer value between registers.  

Components:  
Program Counter:  
Point to next instruction in memory after execution unless overwrriten (jump).  
Instruction Byte:  
IB[7-6] -> operation  
00 -> read immediate value from input and store in register 0  
01 -> perform ALU computation with values in register 1 and 2  
10 -> copy from source to destination:  
    IB[5-3] -> source register/input  
    IB[2-0] -> destination register/output  
11 -> dudge if condition is met to perform Jump

![TuringComplete](https://user-images.githubusercontent.com/64894558/145481857-c7e2c59e-8f89-4da0-8133-64800e690bf8.png)

### Arithmetic Engine
An ALU that can perform 6 types of instructions on two bytes of input:  
000 OR  
001 AND  
010 NOR  
011 AND  
100 ADD  
101 SUB  

![ArithmeticEngine](https://user-images.githubusercontent.com/64894558/145477675-67ade6d1-5f75-44cf-9d0a-53226878f3bf.png)

### Instruction Decoder
A 2 to 4 decoder that reads the instruction from the two most significant bits

![InstructionDecoder](https://user-images.githubusercontent.com/64894558/145478134-cea1bcbe-54d7-4bbb-ad90-251096681c47.png)

### Conditions
A component that outputs one if the input value matches the condition from instruction byte:  
001 -> true if input = 0  
010 -> true if input < 0  
011 -> true if input <= 0  
100 -> always true  
101 -> true if input != 0  
110 -> true if input >= 0  
111 -> true if input > 0  

![Conditions](https://user-images.githubusercontent.com/64894558/145478342-c4224dda-b93b-4358-9cbe-ea6d2ec7c78b.png)

