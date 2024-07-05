# HNCDI Explain: Mathematical Fundamentals of Quantum Computing

This repository contains files for the HNCDI Explain course, "Mathematical Fundamentals of Quantum Computing".

There are two exercises:

1. ```1-bell-state-exercise-ibmq.ipynb``` You need to create a Bell state as has been done previously with the IBM Quantum Composer. You will need to input a number of qubits and a number of classical bits to successfully create the circuit, then run on a simulator and real quantum hardware.

2. ```2-pi-estimate-exercise.ipynb``` This excercise uses simulators. You can choose to run this on your personal machine (if you feel confident to), or in a colab instant. You will need to input an upper limit of qubits and a number of shots to successfully converge to the true value of $\pi$. 

You can get this code in a few different ways, pick whichever you feel confident to do.

1. Use the provided links to load the notebooks in a Google Colab environment (Please note that you will require a Google account and an IBM quantum account),
    - Exercise 1: https://colab.research.google.com/github/philipparubin/HNCDI-Explain-Beginners-Guide-to-QC/blob/main/1-bell-state-exercise-ibmq.ipynb
    - Exercise 2: https://colab.research.google.com/github/philipparubin/HNCDI-Explain-Beginners-Guide-to-QC/blob/main/2-pi-estimate-exercise.ipynb

2. Run it locally
    Either:
        - **Clone/Download:** Clone/Download this respository and load it using your favourite notebook environment. 
        - If you would like to run the simulator exercises on your local machine, you can use poetry for notebook requirements. 

``` 
pip install poetry
poetry install
```
