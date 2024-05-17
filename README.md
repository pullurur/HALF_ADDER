**Aim:**

To simulate and synthesis half adder using vivado.

**Apparatus Required:**

vivado 2023.2 software.

**Procedure:**

STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button. Type the code and save it.

STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.

STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7 compare the output with truth table.

**Truth Table:**

![301802062-fe672c28-5c6a-4355-b70f-b40bce63880d](https://github.com/pullurur/HALF_ADDER/assets/161436550/9fb6d728-18a9-4806-af9e-9acd23f39dde)

**Circuit Diagram**

![301802366-5f1a79a7-73c2-4b99-a40d-afa2a20c74ac](https://github.com/pullurur/HALF_ADDER/assets/161436550/826ff9b9-ae72-4f16-bd38-13a20fe5d204)

**Sum = A XOR B**

![301802521-020e1531-1c11-42e5-9f27-f09ba459984d](https://github.com/pullurur/HALF_ADDER/assets/161436550/30047051-4c70-45a7-9171-2cbff087eb9b)

**Carry = A AND B**

![301802713-988ae131-0822-4d23-941b-eaafad349a72](https://github.com/pullurur/HALF_ADDER/assets/161436550/fd0ddc31-629c-453c-8388-596d401eb87d)

**Program:**

module Half_adder(a,b,sum,carry);

input a,b;

output sum,carry;

xor g1(sum,a,b);

and g2(carry,a,b);

endmodule

**Output:**

![318192390-9bcf556a-6ae7-4c5b-80af-878c655926c8](https://github.com/pullurur/HALF_ADDER/assets/161436550/0c55835a-2af1-462c-97eb-d97b9b15d8fa)

**Result:**

Thus the verilog program for half adder has been simulated and verified successfully.
