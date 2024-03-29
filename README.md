### Study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by: Meenu.S
 RegisterNumber: 212223230124
 ~~~
module LogicGates(a,b,and_out,or_out,not_out,xor_out,xnor_out,nand_out,nor_out);
input a,b;
output and_out,or_out,not_out,xor_out,xnor_out,nand_out,nor_out;
and g1(and_out,a,b);//output should be follwed by input.
or g2(or_out,a,b);
not g3(not_out,a);
xor g4(xor_out,a,b);
xnor g5(xnor_out,a,b);
nand g6(nand_out,a,b);
nor g7(nor_out,a,b);
endmodule 
 ~~~
![Screenshot 2024-03-07 093452](https://github.com/Meenu2823/study-of-basic-gates/assets/139416219/e9ebc1d6-89de-4a77-846e-84fcffa9c6e2)

**Logic symbol & Truthtable**

![Logic gates symbol](https://github.com/Meenu2823/study-of-basic-gates/assets/139416219/62d3f155-880d-4140-a853-209b84b384df)

![image](https://github.com/keerthanapillaram/study-of-basic-gates/assets/145743072/c27b0a4a-e6bd-4064-b214-e65fcf5b5303)

**RTL realization Output:** 
![image](https://github.com/Meenu2823/study-of-basic-gates/assets/139416219/8ce8fb81-8518-49f0-9eb5-1e6d8bf99339)

![Screenshot 2024-03-07 093359](https://github.com/Meenu2823/study-of-basic-gates/assets/139416219/1b2064ba-6524-43cd-8e46-53e43d2da502)


**Result:**

Thus,the truth table of logic gates has been studied and verified in Quartus II using Verilog programming.

