# CircuitDesignPractices
Records from Turing Complete

## Basic Logic


#### NOT Gate
Since the inputs are always the same, result will be the complement of the input.

![NotGate](https://user-images.githubusercontent.com/64894558/145147238-7df0f360-4ce1-42b6-a422-baf86c81adc1.png)

#### NOR Gate
Take the complement of two inputs so output of NAND will only be 0 if two inputs are both 0. Then NOT the output to get the reversed result.

![NorGate](https://user-images.githubusercontent.com/64894558/145147253-24b62caf-fec6-4776-b5d9-8ae0fd640b34.png)

#### OR Gate
Same as NOR, without complementing NAND output.

![OrGate](https://user-images.githubusercontent.com/64894558/145147835-2fce94c1-b864-4cfa-a624-4fffe66b476e.png)

#### AND Gate
The complement of NAND.

![AndGate](https://user-images.githubusercontent.com/64894558/145147848-d594626b-19e8-4ae8-8129-43f157deb22c.png)

#### Always On
One of the input itself and its complemet must be 1.

![AlwaysOn](https://user-images.githubusercontent.com/64894558/145150096-17517de5-074d-4ca6-aaf4-f0a5a5fe3aae.png)

#### Second Tick
Nothing Special.

![SecondTick](https://user-images.githubusercontent.com/64894558/145150098-05d61689-3b31-4a1c-ae47-29f711de4c20.png)

#### XOR Gate
When the inputs are the both 1, AND will output 0. When none of them is 0, OR will give a 0.

![XorGate](https://user-images.githubusercontent.com/64894558/145150105-c85d59b1-aeb7-493c-8474-0f648e5531ab.png)

Achievement #1 -- building an XOR gate with only 4 NAND gates
Draw out the truth table for NAND, then it will be very easy.

![XorGate_Achievement](https://user-images.githubusercontent.com/64894558/145150112-87c4bb3f-9c63-4240-873c-b4413e190d66.png)

#### Bigger OR Gate
Just bigger.

![BiggerOrGate](https://user-images.githubusercontent.com/64894558/145150874-61f46e46-f3fd-4290-873e-42bf70257790.png)

#### Bigger AND Gate
Still, just bigger.

![BiggerAndGate](https://user-images.githubusercontent.com/64894558/145150878-de74315c-48ed-4aa8-a361-00dd60f64123.png)

#### Xnor Gate
Complement of XOR.

![XnorGate](https://user-images.githubusercontent.com/64894558/145150879-4b19f061-44e6-4eff-950e-35c07af9bcf2.png)






Double Trouble

Odd Number of Signals

Counting Signals

Half Adder

Double the Number 

Full Adder

Tangled Gates

Byte Or
Perform bitwise OR.


Byte Not
Invert the value in each bit position.

Adding Bytes
Adding each bit together and in each calculation, include the carry out from previous bit position each time.

Saving Gracefully

Switch


Bit Inverter
If you look at the desired output, you will find that it's just the behavior of an XOR gate.

Input Selector

Signed Negator

Saving Bytes

1 Bit Decoder
Use a NOT gate to output only one 1 at a time.


3 Bit Decoder
Similar idea as 1 Bit Decoder, only one output is active at a time corresponding to the value from the input.


One Way

Little Box

Counter




