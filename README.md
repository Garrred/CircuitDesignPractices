# CircuitDesignPractices
Records from Turing Complete

###Basic Logic 

NOT Gate
![NotGate](https://user-images.githubusercontent.com/64894558/145147238-7df0f360-4ce1-42b6-a422-baf86c81adc1.png)
Since the inputs are always the same, result will be the complement of the input.

NOR Gate
![NorGate](https://user-images.githubusercontent.com/64894558/145147253-24b62caf-fec6-4776-b5d9-8ae0fd640b34.png)
Take the complement of two inputs so output of NAND will only be 0 if two inputs are both 0. Then NOT the output to get the reversed result.

OR Gate
![OrGate](https://user-images.githubusercontent.com/64894558/145147835-2fce94c1-b864-4cfa-a624-4fffe66b476e.png)
Same as NOR, without complementing NAND output.

AND Gate
![AndGate](https://user-images.githubusercontent.com/64894558/145147848-d594626b-19e8-4ae8-8129-43f157deb22c.png)
The complement of NAND.

Double Trouble:
A circuit that output 1 when more than 2 of the inputs are 1
![DoubleTrouble](https://user-images.githubusercontent.com/64894558/144798690-397dec03-702e-4d92-a5c4-62874ba965a4.png)

3-8 Decoder:
3-8 Decoder using not gates and 3-input and gates
![3-8Decoder](https://user-images.githubusercontent.com/64894558/144799076-93dac7aa-3c14-4792-ba87-bc2f43bdc505.png)
