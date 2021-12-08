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

#### Double Trouble
A circuit that output 1 when more than 2 of the inputs are 1

![DoubleTrouble](https://user-images.githubusercontent.com/64894558/144798690-397dec03-702e-4d92-a5c4-62874ba965a4.png)

#### 3-8 Decoder
3-8 Decoder using not gates and 3-input and gates

![3-8Decoder](https://user-images.githubusercontent.com/64894558/144799076-93dac7aa-3c14-4792-ba87-bc2f43bdc505.png)
