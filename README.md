# NandGame

Solutions for The Nand Game, a game that teaches the fundamentals of computing by building a computer from scratch. Each level is accompanied by images of the logic gates used to build the components.



## Table of Contents

- [Levels](#levels)
  - [Logic Gates](#logic-gates)
    - [NAND Gate](#nand-gate)
    - [Invert](#invert)
    - [AND Gate](#and-gate)
    - [OR Gate](#or-gate)
    - [XOR Gate](#xor-gate)
  - [Arithmetic](#arithmetic)
    - [Half Adder](#half-adder)
    - [Full Adder](#full-adder)
    - [Multi-bit Adder](#multi-bit-adder)
    - [Increment](#increment)
    - [Subtraction](#subtraction)
    - [Equal to Zero](#equal-to-zero)
    - [Less than Zero](#less-than-zero)
  - [Switching](#switching)
    - [Selector](#selector)
    - [Switch](#switch)
  - [Arithmetic Logic Unit](#arithmetic-logic-unit)
    - [Logic Unit](#logic-unit)
    - [Arithmetic Unit](#arithmetic-unit)
    - [ALU](#alu)
    - [Condition](#condition)
  - [Memory](#memory)
    - [Latch](#latch)
    - [Data Flip-Flop](#data-flip-flop)
    - [Register](#register)
    - [Counter](#counter)
    - [RAM](#ram)
  - [Processor](#processor)
    - [Combined Memory](#combined-memory)
    - [Instruction](#instruction)
    - [Control Unit](#control-unit)
    - [Computer](#computer)
    - [Input and Output](#input-and-output)
- [Author](#author)



## Levels

## Logic Gates

### NAND Gate
<img src="logic_gates/nand.png" width="500">
2 components used. This is the simplest possible solution!

### Invert
<img src="logic_gates/invert.png" width="500">
1 component used. 1 NAND gate in total. This is optimal!

### AND Gate
<img src="logic_gates/and.png" width="500">
2 components used. 2 NAND gates in total. This is optimal!

### OR Gate
<img src="logic_gates/or.png" width="500">
3 components used. 3 NAND gates in total. This is optimal!

### XOR Gate
<img src="logic_gates/xor.png" width="500">
4 components used. 4 NAND gates in total. This is optimal!


## Arithmetic

### Half Adder
<img src="arithmetic/half_adder.png" width="500">
5 components used. 5 NAND gates in total. This is optimal!

### Full Adder
<img src="arithmetic/full_adder.png" width="500">
9 components used. 9 NAND gates in total. This is optimal!

### Multi-bit Adder
<img src="arithmetic/multibit_adder.png" width="500">
2 components used. 18 NAND gates in total. This is optimal!

### Increment
<img src="arithmetic/increment.png" width="500">
2 components used. (Not counting 0 which does not contain any logic.) 145 NAND gates in total. This is the simplest possible solution!

### Subtraction
<img src="arithmetic/subtraction.png" width="500">
3 components used. (Not counting 0 which does not contain any logic.) 161 NAND gates in total. This is the simplest possible solution!

### Equal to Zero
<img src="arithmetic/equal_to_zero.png" width="500">
4 components used. 10 NAND gates in total. This is optimal!

### Less than Zero
<img src="arithmetic/less_than_zero.png" width="500">
0 components used. (Not counting splitter which does not contain any logic.) 0 NAND gates in total. This is the simplest possible solution!


## Switching

### Selector
<img src="switching/selector.png" width="500">
4 components used. 4 NAND gates in total. This is optimal!

### Switch
<img src="switching/switch.png" width="500">
4 components used. 4 NAND gates in total. This is optimal!


## Arithmetic Logic Unit

### Logic Unit
<img src="alu/logic_unit.png" width="500">
7 components used. 352 NAND gates in total. This is the simplest possible solution!

### Arithmetic Unit
<img src="alu/arithmetic_unit.png" width="500">
5 components used. (Not counting 0 which does not contain any logic.) 434 NAND gates in total. This is the simplest possible solution!

### ALU
<img src="alu/alu.png" width="500">
6 components used. (Not counting 0 which does not contain any logic.) 1042 NAND gates in total. This is the simplest possible solution!

### Condition
<img src="alu/condition.png" width="500">
8 components used. (Not counting is neg which does not contain any logic.) 56 NAND gates in total. This is optimal!


## Memory

### Latch
<img src="memory/latch.png" width="500">
1 component used. 4 NAND gates in total. This is optimal!

### Data Flip-Flop
<img src="memory/data_flipflop.png" width="500">
5 components used. 13 NAND gates in total. This uses the fewest possible components. (But it is possible to solve with a lower total of NAND gates.)

### Register
<img src="memory/register.png" width="500">
2 components used. 26 NAND gates in total. This is the simplest possible solution!

### Counter
<img src="memory/counter.png" width="500">
4 components used. (Not counting 0 which does not contain any logic.) 418 NAND gates in total. This is the simplest possible solution!

### RAM
<img src="memory/ram.png" width="500">
4 components used. 484 NAND gates in total. This is the simplest possible solution!


## Processor

### Combined Memory
<img src="processor/combined_memory.png" width="500">
3 components used. 416 NAND gates in total. And 123904 for each kilobyte of RAM. This is the simplest possible solution!

### Instruction
<img src="processor/instruction.png" width="500">
3 components used. (Not counting splitter which does not contain any logic.) 1162 NAND gates in total.

### Control Unit
<img src="processor/control_unit.png" width="500">
10 components used. (Not counting splitter and 0 which does not contain any logic.) 1297 NAND gates in total.

### Computer
<img src="processor/computer.png" width="500">
4 components used. (Not counting clock which does not contain any logic.) 2131 NAND gates in total. And 123904 for each kilobyte of RAM. (ROM storage not counted) This is the simplest possible solution!

### Input and Output
<img src="processor/input_output.png" width="500">
3 components used. (Not counting lamp and button and bundler and splitter which does not contain any logic.) 6 NAND gates in total.



## Author

👤 **Aras Güngöre**

- LinkedIn: [@arasgungore](https://www.linkedin.com/in/arasgungore)
- GitHub: [@arasgungore](https://github.com/arasgungore)
