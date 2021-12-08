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


## Arithmetic && Memory

#### Double Trouble
![DoubleTrouble](https://user-images.githubusercontent.com/64894558/145280128-e6a394d0-f24b-4079-a435-bd4bab61056e.png)
![DoubleTrouble_Improved](https://user-images.githubusercontent.com/64894558/145280133-07a3ca5c-5568-44c7-97fc-3e707a65a7bf.png)

#### Odd Number of Signals
![OddNumberOfSignals](https://user-images.githubusercontent.com/64894558/145280156-c5129d14-5b46-4580-986d-ee8037764ea3.png)

#### Counting Signals
![CountingSignals_Improved](https://user-images.githubusercontent.com/64894558/145280194-94e9b72b-40f4-419a-a933-b5eee7bc7e03.png)



#### Half Adder
![HalfAdder](https://user-images.githubusercontent.com/64894558/145280213-714682d8-406d-49eb-9d96-152a57a950fc.png)

#### Double the Number 
![DoubleTheNumber](https://user-images.githubusercontent.com/64894558/145280228-fbfda9be-11ab-484a-ab18-2e668303836f.png)

#### Full Adder
![FullAdder](https://user-images.githubusercontent.com/64894558/145280219-8809df6b-4559-485a-9212-7f9225e38bae.png)

#### Tangled Gates
![TangledGates](https://user-images.githubusercontent.com/64894558/145280252-8529b984-9e11-43ba-b66c-810ad277c550.png)

#### Byte Or
Perform bitwise OR.
![ByteOr](https://user-images.githubusercontent.com/64894558/145280281-909c4f5b-f0f8-4367-beb3-0d034a6ce921.png)


#### Byte Not
Invert the value in each bit position.
![ByteNot](https://user-images.githubusercontent.com/64894558/145280300-82e37fcd-52fb-4dbc-992e-f2cd51919748.png)

#### Adding Bytes
Adding each bit together and in each calculation, include the carry out from previous bit position each time.
![AddingBytes](https://user-images.githubusercontent.com/64894558/145280305-458da997-ee38-41b0-9d16-c891d9a6988f.png)

#### Saving Gracefully
![SavingGracefully](https://user-images.githubusercontent.com/64894558/145280324-cebf67b1-54ec-403a-9210-836f9f72ef8f.png)

#### Switch
![Switch](https://user-images.githubusercontent.com/64894558/145280354-3b9ed8de-3ae5-4564-bd57-79eb3cdac758.png)


#### Bit Inverter
If you look at the desired output, you will find that it's just the behavior of an XOR gate.
![BitInverter](https://user-images.githubusercontent.com/64894558/145280376-dd5c07b5-87d7-4f76-a470-a1adad5bdf9c.png)

#### Input Selector
![InputSelector](https://user-images.githubusercontent.com/64894558/145280383-5f092b67-87ad-442f-bad4-eba88c6dd27f.png)

#### Signed Negator
![SignedNegator](https://user-images.githubusercontent.com/64894558/145280410-6591146e-e28e-469e-93a8-aeeda3a428e6.png)

#### Saving Bytes
![SavingBytes](https://user-images.githubusercontent.com/64894558/145280424-fd670c45-21e0-4cb5-9efe-a637e81e413d.png)

#### 1 Bit Decoder
Use a NOT gate to output only one 1 at a time.
![1BitDecoder](https://user-images.githubusercontent.com/64894558/145280439-724cee2b-8079-4172-b7c6-6255553d09d2.png)


#### 3 Bit Decoder
Similar idea as 1 Bit Decoder, only one output is active at a time corresponding to the value from the input.
![3BitDecoder](https://user-images.githubusercontent.com/64894558/145280450-fd045173-7d8d-45b8-822b-dc6fbaabb424.png)


#### One Way
![OneWay](https://user-images.githubusercontent.com/64894558/145280464-5b876ce7-dd61-425c-95ce-73beca9b48ac.png)

#### Little Box
![LittleBox](https://user-images.githubusercontent.com/64894558/145280476-919afe6b-098f-4530-a0fd-fa3b9576881b.png)

#### Counter
![Counter](https://user-images.githubusercontent.com/64894558/145280488-4eec511e-f952-48f8-be14-f83978de14c7.png)



