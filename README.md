# 6502-SuperCalc


OVERVIEW
--------------------------------------------------
The purpose of this project was to implement a high precision calculator in 6502 Assembly language for the [Computer Organization and Architecture] course. It was made at the Computer Science undergraduate program from University of São Paulo (ICMC - USP).

WHAT IS 6502 ASSEMBLY?
--------------------------------------------------
6502 Assembly was used to write programs for the Atari 2600, Apple II, Commodore 64 and Nintendo Entertainment System.
It has two index-registers (X and Y) and an accumulator (A).

PROJECT
--------------------------------------------------
The project is about a high precision calculator that is only limited through the amount of memory.
There are 3 types of operation you can make:
* Add (positive integers)
* Subtract (positive integers)
* Multiply (two integer values)

HOW TO PLACE VALUES
--------------------------------------------------
At the bottom of the code you can modify two arrays `V1` and `V2`.
The result will be stored inside an array called `Resultado`.

HOW TO ASSEMBLE
--------------------------------------------------
```bash
	1. Extract the 6502 simulator zip file (This version is Windows only)
	2. Load the code
	3. Assemble it (F6)
	4. Run it (F5)
	5. Click on the View tab to select what you want to see (Memory/Stack/Registers)
```
CREDITS
--------------------------------------------------
- Renato José Alves da Silva
- Wesley Tiozzo

MORE INFO
--------------------------------------------------
* Please check the file `project specification.pdf` to know more about this project.
