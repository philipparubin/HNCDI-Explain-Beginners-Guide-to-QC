# HNCDI Explain: Mathematical Fundamentals of Quantum Computing

This repository contains files for the HNCDI Explain course, "Mathematical Fundamentals of Quantum Computing".

There are two exercises:

1. ```1-bell-state-exercise-ibmq.ipynb``` Upload this file from within the IBM Quantum Lab. You need to create a Bell state as has been done previously with the IBM Quantum Composer. You will need to input a number of qubits and a number of classical bits to successfully create the circuit, then run on a simulator and real quantum hardware.

2. ```2-pi-estimate-exercise.ipynb``` This excercise uses simulators. You can choose to run this on your personal machine (if you feel confident to), or in the IBM Quantum Lab. You will need to input an upper limit of qubits and a number of shots to successfully converge to the true value of $\pi$. 

You can get this code in a few different ways, pick whichever you feel confident to do.

Either:
- **Clone:** Clone this respository and upload the .ipynb files to the IBM Quantum Lab. Run all cells.
- **Download:** Go to Code > Download ZIP. Open the ZIP file and upload the .ipynb files to the IBM Quantum Lab. Run all cells.
- **Copy and Paste from GitHub:** Create a new notebook in the IBM Quantum Lab. Copy and paste the commands one cell at a time from the .ipynb files into your new notebook and run each cell with Shift-Enter.

If you would like to run the simulator exercises on your local machine, you can use poetry for notebook requirements.

``` 
pip install poetry
poetry install
```
