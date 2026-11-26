# StackPVM

A stack-based Python Virtual Machine (PVM) written in Python, adapted from [`cslarsen/python-simple-vm`](https://github.com/cslarsen/python-simple-vm) and extended with custom minute-task operations.

## Added Operations in `vm.py`

- `square`: Pops a number and pushes its square (`n * n`).
- `abs`: Pops a number and pushes its absolute value (`abs(n)`).
- `max`: Pops two numbers and pushes the greater one.
- `min`: Pops two numbers and pushes the smaller one.
- `even`: Pops a number and pushes `True` if even, otherwise `False`.
- Updated `parse()` to skip `NEWLINE` and `NL` tokens so interactive commands run without errors.

## How to Run

Open a terminal in the project folder and run:

'''bash
python vm.py'''


### Sample Commands

5 square println
0 9 - abs println
12 25 max println
12 25 min println
8 even println
7 even println
Type exit (or press Ctrl+D / Ctrl+C) to quit.

### Credits

Base VM code adapted from cslarsen/python-simple-vm.
