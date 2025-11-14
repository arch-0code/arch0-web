# arch0-web
An IntelHex Fork
Arch_0 (also called Architect_0) is a custom, low-level-inspired programming language designed to mimic machine code, Intel HEX, and register-based operations, while still being approachable for creative experimentation.

It is built around a register-command structure (x0 x0, $ style) and supports:

Basic output: print single characters or strings using x8 x0, $

Arithmetic operations: add, subtract, multiply, modulo using x8 x1/x2/x3/x4, a_b syntax

User-Friendly Mode (UFM): type full words or strings for simplified output

Extended Commands (ECMD): add custom commands like clearing output (cls) or adding new features

Arch_0 is designed for experimentation and learning low-level thinking, while keeping a playful, creative coding style. It is not bound by strict compiler rules, allowing users to type, copy, and run code freely in a web-based interpreter.

Use Cases:

Educational exploration of low-level concepts

Text-based games, emulators, or mini-interpreters

Creative coding exercises in a register-command style

Example Code – Hello World in Arch_0:

** FOLDER: HelloWorld
x0 x0, $        
x1 x0, 48H      
x8 x0, $        
x1 x0, 65H      
x8 x0, $        
x1 x0, 6CH      
x8 x0, $        
x1 x0, 6CL      
x8 x0, $        
x1 x0, 6FH      
x8 x0, $        
&& End HelloWorld
