# Quantum-computing
Analysing the quantum circuit and infering the output.

Quirk Quantum Simulator - https://algassert.com/quirk for circuit analysis.


Consider the following quantum circuit:<br> <br>
![image](https://user-images.githubusercontent.com/84000497/187093051-b513dafe-afc9-41c5-a1c9-b1338d628d17.png)

It consists of two CNOT gates in the middle of the circuit. The two-qubit input quantum
register |x⟩ is in some arbitrary quantum state that forms its input and can be set by the
user. The other two-qubit input quantum register |00⟩ is in the ground state. The gate F is
an unknown quantum operation (this means it is an arbitrary, but fixed gate on two qubits,
but you do not know what it does). The gate F−1 computes the inverse operation of F.
1. Analyse the operation of the circuit to determine what the values of the two two-qubit
output quantum registers |A⟩ and |B⟩ are, depending on the properties of F and |x⟩.
Clearly justify your answer.
2. Explain how you could, if possible, determine the operation of the gate F from this
circuit (you can execute the circuit as many times as you wish). Furthermore, discuss
what this means for the difference between quantum computing and a classical
computing paradigm of your choice (working with bits instead of qubits).
