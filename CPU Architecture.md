# CPU Architecture


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

