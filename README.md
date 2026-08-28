## NAND Gate Implementation in SystemVerilog

A **NAND gate** (Not-AND) is a universal digital logic gate. It produces a low output (`0`) only if all its inputs are high (`1`).

### Truth Table

| Input (A) | Input (B) | Output (Y) |
| :---: | :---: | :---: |
| 0 | 0 | 1 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

### Features
* Universal gate behavior implemented via dataflow modeling (`~&` or `~(a & b)`).
* Self-checking testbench covering all 4 input combinations.
* VCD waveform generation for logic analysis.



### waveform
<img width="1907" height="440" alt="image" src="https://github.com/user-attachments/assets/b41633ba-0ec4-4a4f-9e7a-32c9352b3217" />
