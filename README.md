#
First Week

Beside classical introduction to the course, the first week of Nan2Tetris part 1 was reserved for Boolean Functions and Gate Logic.

As most people probably know, the only thing that every computer really understand are 0 and 1. All of the other things are actually abstraction and product of operations that we can do only with those two, I would say, powerfull numbers.

At the level of physics, zeroes and ones actually represents if there is electricity flowing through the circuits. If there is electricity, we say that result is 1, and if there is not, result is 0.

Since we have just two values needed for computer to work \(1 or 0, ON or OFF, TRUE or FALSE - those are actually the same thingswhen it comes to saying if there is electricity\) we can represent all kinds of functions and operations on them using Boolean Logic and Functions, from which we create so called Logic Gates.

I won't spend too much time explaining Boolean Logic and what are AND, OR, NOT operations, their truth tables... Instead, I'll focus on explaining what do you need to do in the first week project.

#### "**GOD" CREATED NAND GATE**

In order to make CPU, RAM memory, registers and other parts of the computer, we first need to make much simpler chips that can do just basic boolean Logic \(or, and, not...\).

Professor Shimon made joke in one of the videos in Week 1 of the course that "God created NAND gate". Actually, team of hardworking scientists managed to create that simple gate, which we can use, believe it or not, to create all other chips in every single computer. What Shimon meant is that with the NAND gate we draw the line and below that line we don't need to care how is NAND gate made and what are the physics laws that apply to it. **We just take NAND gate for granted, thats all**.

NAND gate in the computer is like one living cell in our body. Group of cells create tissues and tissues create organs. Well, almost the same principle is used in building parts of the computer. NAND gate creates basic chips, \(I'll get to basic chips in a minute\), basic chips makes CPU, RAM memory, register and other parts which altogether creates computer.

We will use NAND gates and connect them in different ways so that as out we get result from the truth table of boolean logic operation that we want to make.

Below, you can see graphic representation of NAND gate and truth table for it.![](https://upload.wikimedia.org/wikipedia/commons/thumb/5/58/Nand-gate-en.svg/2000px-Nand-gate-en.svg.png)**NAND gate truth table:**

| **A** | **B** | **OUT** |
| :---: | :---: | :---: |
| 0 | 0 | 1 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

#### What chips we need to make in project 1 of Nand2Tetris Course?

| ELEMENTARY LOGIC GATES | 16-BIT VARIANTS | MULTI-WAY VARIANTS |
| :---: | :---: | :---: |
| Not | Not16 | Or8Way |
| And | And16 | Mux4Way16 |
| Or | Or16 | Mux8Way16 |
| Xor | Mux16 | DMux4Way |
| Mux | | DMux8Way |
| DMux | | |

