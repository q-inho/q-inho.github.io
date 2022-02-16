---
title:  "[Quantum Computing] What are Bits"

categories:
  - QC Fundamentals
tags:
  - [Quantum Computing, Electrical Engineering]

toc: true
toc_sticky: true
 
date: 2022-02-15
last_modified_at: 2022-02-15
---
# Bits

![Quantum Computing Fundamentals](https://user-images.githubusercontent.com/79438062/153969577-4ca76d42-b801-4d31-bc3e-abfe1b5bbeac.jpg)

It is helpful to study how do quantum computers are designed if you understand basic classical computing. The following graph shows how do classical computers and quantum computers are different in each concept.

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

## States

Bits have two states that are zeros and ones. Let's look at some examples.

### Coins

![business-gcce9264c2_1920](https://user-images.githubusercontent.com/79438062/154178982-1539025e-07db-4791-a552-49d56e413b72.jpg)

The coin has two possible states, heads(H) and tails(T). If we assume that there are three coins, we can know that there are 8 possible states, since each coin has two possible states. We use simple calculation for the total number of states, \\(2\times2\times2=2^3=8 \\)

\\[HHH, HHT, HTH, HTT, THH, THT, TTH, TTT \\]

### Dices

![cube-g579a7eaad_1280](https://user-images.githubusercontent.com/79438062/154179422-8f76b8d6-2c57-4868-bf39-6bcbe30ade0a.jpg)

The dice has 6 possible states, 1 through 6. If we assume that there are two dice, we can know that there are 36 possible states, since each dice has 6 possible states. We use simple calculation for the total number of states, \\(6\times6=6^2=36\\)

\\[(1,1),(1,2),(1,3),(1,4),(1,5),(1,6) \\]
\\[(2,1),(2,2),(2,3),(2,4),(2,5),(2,6) \\]
\\[(3,1),(3,2),(3,3),(3,4),(3,5),(3,6) \\]
\\[(4,1),(4,2),(4,3),(4,4),(4,5),(4,6) \\]
\\[(5,1),(5,2),(5,3),(5,4),(5,5),(5,6) \\]
\\[(6,1),(6,2),(6,3),(6,4),(6,5),(6,6) \\]

## Encoding Information

We can use these coins and dices to encode the information. By giving each state the meaning, we can represent each information by the possible configuration of coins and dices. If we play the game, this information can be encoded with three coins or two dices as shown in this table. The rest of the states do not contain any information if the number of encoded information is less than the possible number of states.

| **Action** | **Coins** | **Dices** |
|------------|-----------|---------|
| Attack     | HHH       | (1,1)   |
| Defense     | HHT       | (1,2)   |
| Recover    | HTH       | (1,3)   |
| Move Up    | HTT       | (1,4)   |
| Move Down  | THH       | (1,5)   |
| Move Left  | THT       | (1,6)   |
| Move Right | TTH       | (2,1)   |

Two states carry the smallest amount of information possible and bit is the smallest unit of classical information.

## Binary

Bit have two possible states that are 0 and 1. So if we have three bits, we know that there are 8 possible states

\\[000, 001, 010, 011, 100, 101, 110, 111 \\]

These numbers are called binary numbers. We can note that these are binary numbers by writing them in this format. 

\\[10101_2\\]

On the other hand, we can note that the number is the decimal number by writing them in this format.

\\[8219_{10}\\]

### Conversion from Binary to Decimal

From the decimal number that we commonly use in daily life, we know what does each integer means. For example, 8219 should mean as follow.

$$
\begin{align*} 8219 =& 8\cdot 1000+2\cdot 100+1\cdot 10+9\cdot 1 \\ =& 8\cdot 10^3+2\cdot 10^2+1\cdot 10^1+9\cdot 10^0 \end{align*}
$$

Similar to Decimal, each integer in binary has meaning as below and can convert the binary number into a decimal number that we are familiar with.

$$
\begin{align*} 10101 =& 1\cdot 2^4+0\cdot 2^3+1\cdot 2^2+0\cdot 2^1+1 \cdot 2^0 \\ =& 1\cdot 16+0\cdot 8+1\cdot 4+0\cdot 2+1 \cdot 1 \\ =& 21 \end{align*}
$$

We can notice that the leftmost number contributes the largest number and we call it the most significant bit. Similarly, the rightmost number contributes the smallest number and we call it the least significant bit.

We can use 8 bits, binary numbers to encode the texts. ASCII, American Standard Code for Information Interchange uses \\(2^8 = 256 \\) possible states to encode each character of text.
[ASCII table](https://www.rapidtables.com/convert/number/binary-to-ascii.html)



##### Reference
* [Wong, T. Introduction to Classical and Quantum Computing. (2022).](http://www.thomaswong.net/)