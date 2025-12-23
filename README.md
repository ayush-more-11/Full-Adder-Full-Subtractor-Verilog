# Full-Adder-Full-Subtractor-Verilog

Verilog implementation and Testbench for Full Adder and Full Subtractor using Gate, Dataflow, Behavioral Level Modelling.

# Full Adder 

Equations : 

Sum = A ⊕ B ⊕ Cin

Cout = AB + BCin + ACin

| A | B | Cin | Sum | Cout |
| - | - | --- | --- | ---- |
| 0 | 0 | 0   | 0   | 0    |
| 0 | 0 | 1   | 1   | 0    |
| 0 | 1 | 0   | 1   | 0    |
| 0 | 1 | 1   | 0   | 1    |
| 1 | 0 | 0   | 1   | 0    |
| 1 | 0 | 1   | 0   | 1    |
| 1 | 1 | 0   | 0   | 1    |
| 1 | 1 | 1   | 1   | 1    |


# Full Subtractor 

Equations :

D = A ⊕ B ⊕ Bin

Bout = A'B + B·Bin + A'·Bin

| A | B | Bin | D | Bout |
| - | - | --- | - | ---- |
| 0 | 0 | 0   | 0 | 0    |
| 0 | 0 | 1   | 1 | 1    |
| 0 | 1 | 0   | 1 | 1    |
| 0 | 1 | 1   | 0 | 1    |
| 1 | 0 | 0   | 1 | 0    |
| 1 | 0 | 1   | 0 | 0    |
| 1 | 1 | 0   | 0 | 0    |
| 1 | 1 | 1   | 1 | 1    |
