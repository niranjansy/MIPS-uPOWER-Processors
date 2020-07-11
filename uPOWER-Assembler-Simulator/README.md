# Assembler and Simulator for the uPOWER ISA

Default registers:
- 0: To store zero
- 30: System Call Code
- 29: Argument for system call
- 28: Output of system call

Requirments:
1. Python 3.x
2. Numpy (pip install numpy)
3. bitstring (pip install bitstring)

Run using:
1. python simulate.py (or python3 simulate.py)  // complete execution
2. python simulate_step.py (or python3 simulate_step.py) // For step-by-step execution

Set the filename parameter in the file mm.py to run the code written in the uPOWER ISA. It should be in a .txt format. 
