# IL
## Hello world in IL programming language

### IL (Instruction Language) is an assembler-like IEC 61131-3 conformal programming language.

### This language supports programming based on an accumulator. The IEC 61131-3 operators are supported as well as multiple inputs / multiple outputs, negations, comments, set / reset of outputs and unconditional / conditional jumps.

### Each instruction is primarily based on the loading of values into the accumulator by using the LD operator. After that the operation is executed with the first parameter taken out of the accumulator. The result of the operation is available in the accumulator, from where you should store it with the ST instruction.

### In order to program conditional executions or loops, IL supports both comparing operators such as EQ, GT, LT, GE, LE, NE and jumps. The latter can be unconditional (JMP) or conditional (JMPC / JMPCN). For conditional jumps, the value of the accumulator is referenced for TRUE or FALSE.