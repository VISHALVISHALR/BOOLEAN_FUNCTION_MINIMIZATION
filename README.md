# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
module experiment2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~c)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/24900248


**RTL realization**![383127164-67542647-c6fb-4065-9d0f-0ce48d11cae0](https://github.com/user-attachments/assets/48b2386f-5ad7-40f9-b2b9-1c2b43a36cf3)

**TRUTHTABLE**
![392007968-0ff0cc8d-a388-4297-ac03-7771303160b7](https://github.com/user-attachments/assets/acc8124a-64e1-423d-b953-3b772e609f67)
![392007889-b2e6f509-64de-444c-a5fa-e40898d2b160 (1)](https://github.com/user-attachments/assets/fc5cbbec-daa2-41f0-8f64-30d63cc68de2)



**Output:**

**RTL**

**Timing Diagram**![387574673-4bfc069b-5f93-4d1a-b89d-8529cbe889b7](https://github.com/user-attachments/assets/fe7335b9-29fd-4b83-8496-5b93c094380a)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

