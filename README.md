# 16_bit_adder_subtractor
It's a calculator to find the sum and subtraction in 2's complement of 2 16-bit number

Circuit for the 16-bit adder and Subtractor 

![Screenshot_20230609_103317](https://github.com/miYo-0/16_Bit_Adder-Subtractor/blob/main/244758319-e7f70c3b-0008-4799-b130-55035a6ada33.png)

# Adder 
To use the circuit as an adder give the adder/subtractor pin value as 0 and as we know the xor of 0 and any number is the number itself so we will get the number B itself and also the cin is 0 so after adding the bits you can see the output in the 7 segment displays.
In case of overflow,  you can see the extra bit as high.

![image](https://github.com/miYo-0/16_Bit_Adder-Subtractor/blob/main/img2.png)

# Subtractor 
To use the circuit as a subtractor use the adder/subtractor pin as 1 and 1^B=B' and cin=1 so after addition we will get the subtraction but as if the carry is high then the answer will remain the same in case of the carry bit as 0 we will again change the number in 
2's complement

2's complement circuit

![image](https://github.com/miYo-0/16_Bit_Adder-Subtractor/blob/main/img3.png)

You can see the final output at 7 segment displays

![image](https://github.com/miYo-0/16_Bit_Adder-Subtractor/blob/main/img4.png)


# verilog coded design 
I am also sharing the Verilog coded design and testbench files with the timing diagram.
we have used the Behavioral Modelling of verilog for the design module.

# Timing diagram of the circuit 

![image](https://github.com/miYo-0/16_Bit_Adder-Subtractor/blob/main/img5.png)
