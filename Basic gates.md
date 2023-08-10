# Basic Logic Gates in Java

Logic gates are fundamental building blocks of digital circuits, enabling various logical and arithmetic operations in computer systems. This repository provides simple Java implementations of basic logic gates along with illustrative examples.

## Table of Contents

- [AND Gate](#and-gate)
- [OR Gate](#or-gate)
- [NOT Gate](#not-gate)
- [XOR Gate](#xor-gate)
- [NAND Gate](#nand-gate)
- [NOR Gate](#nor-gate)
- [XNOR Gate](#xnor-gate)
- [Usage](#usage)

## AND Gate
The AND gate produces an output of 1 only when both input signals are 1. It performs a logical AND operation.

Truth Table:
| Input A | Input B | Output |
|---------|---------|--------|
|    0    |    0    |    0   |
|    0    |    1    |    0   |
|    1    |    0    |    0   |
|    1    |    1    |    1   |

Example:
```java
int result = LogicGates.ANDGate(1, 0);  // Output will be 0
```

## OR Gate
The OR gate produces an output of 1 if at least one input signal is 1. It performs a logical OR operation.

Truth Table:
| Input A | Input B | Output |
|---------|---------|--------|
|    0    |    0    |    0   |
|    0    |    1    |    1   |
|    1    |    0    |    1   |
|    1    |    1    |    1   |

Example:
```java
int result = LogicGates.ORGate(0, 1);  // Output will be 1
```

## NOT Gate
The NOT gate (inverter) produces the opposite of the input signal at its output.

Truth Table:
| Input | Output |
|-------|--------|
|   0   |    1   |
|   1   |    0   |

Example:
```java
int result = LogicGates.NOTGate(0);  // Output will be 1
```

## XOR Gate
The XOR gate produces an output of 1 when the inputs are different.

Truth Table:
| Input A | Input B | Output |
|---------|---------|--------|
|    0    |    0    |    0   |
|    0    |    1    |    1   |
|    1    |    0    |    1   |
|    1    |    1    |    0   |

Example:
```java
int result = LogicGates.XORGate(1, 0);  // Output will be 1
```

## NAND Gate
The NAND gate produces an output of 0 only when both input signals are 1. It is the opposite of the AND gate.

Truth Table:
| Input A | Input B | Output |
|---------|---------|--------|
|    0    |    0    |    1   |
|    0    |    1    |    1   |
|    1    |    0    |    1   |
|    1    |    1    |    0   |

Example:
```java
int result = LogicGates.NANDGate(1, 1);  // Output will be 0
```

## NOR Gate
The NOR gate produces an output of 0 if at least one input signal is 1. It is the opposite of the OR gate.

Truth Table:
| Input A | Input B | Output |
|---------|---------|--------|
|    0    |    0    |    1   |
|    0    |    1    |    0   |
|    1    |    0    |    0   |
|    1    |    1    |    0   |

Example:
```java
int result = LogicGates.NORGate(0, 0);  // Output will be 1
```

## XNOR Gate
The XNOR gate produces an output of 1 when the inputs are the same. It is the complement of the XOR gate.

Truth Table:
| Input A | Input B | Output |
|---------|---------|--------|
|    0    |    0    |    1   |
|    0    |    1    |    0   |
|    1    |    0    |    0   |
|    1    |    1    |    1   |

Example:
```java
int result = LogicGates.XNORGate(1, 1);  // Output will be 1
```

## Usage
To use these logic gates, you can call their respective methods from the `LogicGates` class. Modify the input values and observe the outputs to understand the behavior of these basic logic gates.

Feel free to explore and experiment with these Java implementations of basic logic gates in your projects.
