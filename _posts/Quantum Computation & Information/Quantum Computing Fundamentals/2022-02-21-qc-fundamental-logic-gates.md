---
title:  "[Quantum Computing] Logic Gates"

categories:
  - QC Fundamentals
tags:
  - [Quantum Computing, Electrical Engineering]

toc: false
toc_sticky: false
 
date: 2022-02-21
last_modified_at: 2022-02-21
---
![Quantum Computing Fundamentals](https://user-images.githubusercontent.com/79438062/153969577-4ca76d42-b801-4d31-bc3e-abfe1b5bbeac.jpg)

# Introduction

We can control the bits by changing the outputs using the logic gates. For comparing the concepts between a classical computer and quantum computing we can refer back to the table from our previous [post](https://q-inho.github.io/qc%20fundamentals/qc-fundamental-Bits/).



| **Concept**                     | **Classical**   | **Quantum**       |
|---------------------------------|-----------------|-------------------|
| Fundamental Unit                | Bit             | Unitary Gates     |
| Gates                           | Logic Gates     | Unitary Gates     |
| Gates Reversible                | Sometimes       | Always            |
| Universal Gate Set (Example)    | {NAND}          | {H, T, CNOT}      |
| Programming Language (Example)  | Verilog         | OpenQASM          |
| Algebra                         | Boolean         | Linear            |
| Error Correcting Code (Example) | Repetition Code | Shor Code         |
| Complexity Class                | P               | BQP               |
| Strong Church-Turing Thesis     | Supports        | Possibly Violates |


# Single-Bit Gates

Single-Bit Gate is a simple gate that has one input bit and one output bit. Since there is only one input bit there are 2 possibilities in single-bit gates. To understand the `circuit diagram`, we read the diagram from left to right. Also, we list the possibilities of the input and output of the gates in a `truth table`. These are the famous gates for single-bit Gates.

## Identity gate

The identity gate/buffer gate does not affect anything to the input bit of the gate. Its output is 0 when input is 0, while its output is 1 when input is 1. Since nothing happens to the input bit, it usually shows and is considered as a wire.

### Circuit Diagram

![identity gate](https://user-images.githubusercontent.com/79438062/154921238-db3fa5f8-5e20-4e50-b905-4de7749c45dd.jpg)


![wire](https://user-images.githubusercontent.com/79438062/154921265-8e078aa1-ea88-4d53-8724-934414a63dac.jpg)

### Truth Table

| \\(A\\) | \\(A\\) |
|-------|-------|
| 0     | 0     |
| 1     | 1     |

## NOT gate

NOT gate/inverter gate flip a bit. Its output is 1 when input is 0, while its output is 0 when input is 1. In the text, the output bit that is the negation of the input bit can be shown as \\(\overline{A}\\) or \\(\neg{A}\\).

#### Circuit Diagram

![NOT gate](https://user-images.githubusercontent.com/79438062/154921318-7a74e024-5338-4d4c-ae9d-e97fb6f2817b.jpg)

#### Truth Table

| \\(A\\) | \\(\overline{A}\\)|
|-------|-------|
| 0     | 1     |
| 1     | 0     |

# Two-Bit Gates

A two-bit gate has two input bits and one output bit. Since there are two input bits, there are 4 possibilities \\((00,01,10,11)\\) in a two-bit gate.

## AND gate

The AND gate outputs 1 when both inputs are 1. We can note standard multiplication works between the inputs for the output bit. 

$$
\begin{align*}
0\cdot 0=0 \\
0\cdot 1=0 \\
1\cdot 0=0 \\
1\cdot 1=1 \\
\end{align*}
$$

In the text, the output bit can be written as \\(AB\\) or \\(A\wedge B\\).

#### Circuit Diagram

![AND gate](https://user-images.githubusercontent.com/79438062/154921349-c44185bb-c9b3-440d-8786-ab54f31bbd41.jpg)

#### Truth Table

| \\(A\\) | \\(B\\) | \\(AB\\) |
|-------|-------|--------|
| 0     | 0     | 0      |
| 0     | 1     | 0      |
| 1     | 0     | 0      |
| 1     | 1     | 1      |

## OR gate

The OR gate outputs 1 when at least one of the input bits is 1. So, it will output 1 except for the case when input bit A is 0 and input bit B is also 0. In the text, the output bit can be written as \\(A+B\\) or \\(A \vee B\\). Since this is not actual addition, it gives out the result as the following equation. 

$$
\begin{align*}
0+ 0=0 \\
0+ 1=1 \\
1+ 0=1 \\
1+ 1=1 \\
\end{align*}
$$

#### Circuit Diagram

![OR gate](https://user-images.githubusercontent.com/79438062/154921399-f12568d3-761f-4eb2-bfaa-7ad2390040ae.jpg)


#### Truth Table

| \\(A\\) | \\(B\\) | \\(A+B\\) |
|-------|-------|--------|
| 0     | 0     | 0      |
| 0     | 1     | 1      |
| 1     | 0     | 1      |
| 1     | 1     | 1      |

## Exclusive OR gate

The Exclusive OR gate/XOR gate outputs 1 when only one of the input bits is 1. So it will output 0 when inputs signals are equal (\\(00\\) or \\(11\\)). In the text, the output bit can be written as \\(A\bigoplus B\\). This signal \\(+\\) means addition modulo 2. It gives out the output by taking the remainder after dividing by 2. For example, when input signal A is 1 and output signal B is 1, we can use addition, \\(1+1=2\\) and divide them by 2 to give out the result that the remainder from this division is 0.

$$
\begin{align*}
1=1 mod 2 \\
0=2 mod 2
\end{align*}
$$

#### Circuit Diagram

![XOR gate](https://user-images.githubusercontent.com/79438062/154921441-7273b5ce-060b-4bc7-afc7-26a1e75ebec0.jpg)



#### Truth Table

| \\(A\\) | \\(B\\) | \\(A\bigoplus B\\) |
|-------|-------|--------|
| 0     | 0     | 0      |
| 0     | 1     | 1      |
| 1     | 0     | 1      |
| 1     | 1     | 0      |

## NAND gate

The NAND gate output is 0 when both inputs are 1. In other input signals, it outputs 1. NAND gate stands for NOT of AND and it shows flipped results of AND gate. In the text, the output bit can be written as \\(\overline{AB}\\).

#### Circuit Diagram

![NAND gate](https://user-images.githubusercontent.com/79438062/154921466-f6925b91-4887-43ec-9786-e6c30504a440.jpg)

#### Truth Table

| \\(A\\) | \\(B\\) | \\(\overline{AB}\\) |
|-------|-------|--------|
| 0     | 0     | 1      |
| 0     | 1     | 1      |
| 1     | 0     | 1      |
| 1     | 1     | 0      |


## NOR gate

The NOR gate output is 0 when at least one of the input bits is 1. So, it will output 1 when both input signal A and input signal B is 0. NOR gate stands for NOT of OR gate and it shows flipped results of OR gate. In the text, the output bit can be written as \\(\overline{A+B}\\).

#### Circuit Diagram

![NOR gate](https://user-images.githubusercontent.com/79438062/154921512-2be55cb0-50e6-4c86-9a30-b508045f783c.jpg)


#### Truth Table

| \\(A\\) | \\(B\\) | \\(\overline{A+B}\\) |
|-------|-------|--------|
| 0     | 0     | 1      |
| 0     | 1     | 0      |
| 1     | 0     | 0      |
| 1     | 1     | 0      |

# Multiple Gates

More complicated and interesting gates can be created by combining the logic gates. For example, we can add 2 AND gates to form 3 inputs – 1 output AND gate.

#### Circuit Design
![circuit1](https://user-images.githubusercontent.com/79438062/154921532-3207a541-f4d7-4c64-80ca-d94c07576f27.jpg)

#### AND gate with 3 inputs

![3-AND gate](https://user-images.githubusercontent.com/79438062/154921566-39fae55a-4060-48b3-912f-cef8e1ce4aa1.jpg)

#### Truth Table

| \\(A\\) | \\(B\\) | \\(C\\) | \\(AB\\) | \\(ABC\\) |
|-------|-------|--------|--------|--------|
| 0     | 0     | 0      | 0      | 0      |
| 0     | 0     | 1      | 0      | 0      |
| 0     | 1     | 0      | 0      | 0      |
| 0     | 1     | 1      | 0      | 0      |
| 1     | 0     | 0      | 0      | 0      |
| 1     | 0     | 1      | 0      | 0      |
| 1     | 1     | 0      | 1      | 0      |
| 1     | 1     | 1      | 1      | 1      |

We can notice that we can create the logic gates as we want. In summary, we can have \\(2^{2^n}\\) possible \\(n\\)-bit logic gates when there are \\(n\\) input bits.

# Universal Gates

According to the previous equation, we may notice that there should be 16 possible two-bit gates, but I only introduced 5 gates. However, these unlisted gates are not necessarily existed as separate gates since these can be reproduced using a few types of gates. A universal gate set is the set of gates that can perform all possible logic operations. {NOT, AND, OR} is a universal gate set and it can create the circuit to perform any truth table.

#### Truth Table

| \\(A\\) | \\(B\\) | \\(C\\) | \\(Output\\) |
|------|------|------|--------|
| 0 | 0 | 0 | 1      |
| 0 | 0 | 1 | 0      |
| 0 | 1 | 0 | 0      |
| 0 | 1 | 1 | 1      |
| 1 | 0 | 0 | 1      |
| 1 | 0 | 1 | 0      |
| 1 | 1 | 0 | 1      |
| 1 | 1 | 1 | 0      |

#### Sum of Product (SOP)

First we may notice from the truth table that the output signal will be 1 when input signal is `000`, `011`, `100` and `110`. For this set of signals, we use negation to show that signal is `0`. For example we can show that input signal A is 0 by writing \\(\overline{A}\\). On the other hand, we can show taht the input signal is 1 by simply writing \\(A\\). After the conversion, we product(multiply) the input signals for the sets that output `1`. From our truth table, we can get \\(\overline{A}\overline{B}C\\), \\(\overline{A} BC\\), \\(A \overline{B} \overline{C}\\) and \\(A B \overline{C} \\). After that we can get add them to get this expression of the circuit of the truth table.

$$
F = \overline{A}\overline{B}C + \overline{A} BC + A \overline{B} \overline{C} + A B \overline{C}
$$

By using this expression, we can draw the circuit diagram.

![circuit3](https://user-images.githubusercontent.com/79438062/154921691-2859b764-6574-4fd5-a800-0820e15521fd.jpg)


##### Reference
* [Wong, T. Introduction to Classical and Quantum Computing. (2022).](http://www.thomaswong.net/)