# Bernstein_Vazirani_Algorithm
Bernstein_Vazirani_Algorithm applied with and without noise simulator 

# BV-Algorithm 
Using a quantum computer, we can solve this problem with 100% confidence after only one call to the function f(x): 
1) Initialize the inputs qubits to the |0> and output to |-> 
2) Apply Hadamard gates to the input register
3) Query the oracle
4) Apply Hadamard gates to the input register
5) Measure

for more information and examples please refer to this Qikit tutorial https://qiskit.org/textbook/ch-algorithms/bernstein-vazirani.html

adding the noise model, we notice the difference between the probabilities of finding different results for the secret string. 

# Requirements
Python 3.x, qiskit

Refrences:
- Qiskit: https://qiskit.org/textbook/ch-algorithms/bernstein-vazirani.html
- IBM Quantum Experience
