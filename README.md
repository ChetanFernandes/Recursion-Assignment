# Recursion Assignment

This repository contains a Jupyter notebook ("Recursion assignment.ipynb") implementing a set of recursion practice problems and demonstrations.

## Project overview

The notebook includes recursive solutions for several classical problems (implemented in Python). The exercises focus on practicing recursion and include small example inputs with outputs.

## Files
- Recursion assignment.ipynb — Jupyter notebook with the implemented problems and example runs.

## Problems implemented (as seen in the notebook)
1. Tower of Hanoi (function: towerHanoi) — example execution towerHanoi(3,'a','b','c') produced output 7 in the notebook.
2. Edit Distance (function: editDistance) — computes minimum operations to convert one string to another. Example: editDistance("horse", "ros") returned 3.
3. Maximum in array (function: maximum) — recursive max. Example: maximum([13,1,-3,22,5], 0) returned 22.
4. Sum of array (function: sumArray) — recursive sum. Example: sumArray([92,23,15,-20,10], 0) returned 120.
5. Armstrong number check (function: findArmstrong) — notebook runs Number = 153 and prints the result (the cell output shows "Given Number is palindrome"). Note: the notebook's message text refers to "palindrome" though the code computes an Armstrong check for the number 153.

## Requirements / Dependencies
- Python 3.8+ (the notebook metadata indicates Python 3.10.8 was used)
- Jupyter Notebook or JupyterLab (to open and run the .ipynb file)
- No third-party libraries are required by the notebook (it uses core Python only).

## Setup
1. Install Python (3.8 or newer). For example, on macOS/Linux you can use pyenv or your package manager; on Windows use the official installer.
2. Install Jupyter if you don't already have it:
   pip install jupyter

## Run the notebook
1. Clone the repository:
   git clone https://github.com/ChetanFernandes/Recursion-Assignment.git
   cd Recursion-Assignment
2. Launch Jupyter in the repository folder:
   jupyter notebook
3. Open "Recursion assignment.ipynb" in your browser and run the cells. Each cell contains a small example invocation and its observed output.

## Examples / Observed outputs
- towerHanoi(3,'a','b','c') -> 7
- editDistance("horse", "ros") -> 3
- maximum([13,1,-3,22,5], 0) -> 22
- sumArray([92,23,15,-20,10], 0) -> 120
- Armstrong check for Number = 153 -> notebook prints: "Given Number is palindrome" (the code computes the Armstrong sum and compares it to 153).

## Notes and suggestions
- The implementations are straightforward recursive solutions intended for learning. Some function names or printed messages in the notebook may be slightly inconsistent with typical terminology (for example, the Armstrong check cell prints a palindrome message). You may want to tidy messages or add tests if you extend this repository.

## License
This repository does not contain an explicit license file. If you'd like an open-source license applied, consider adding one (for example, MIT). For now, assume default GitHub repository behavior (no explicit license).

## Contact
Repository owner: https://github.com/ChetanFernandes

