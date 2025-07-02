
# Steane Error Correction Simulation

This project simulates the full cycle of encoding, noise, syndrome measurement, error correction, and decoding using the **Steane \[\[7,1,3]] quantum error-correcting code** in Qiskit.

The code demonstrates how to:

* Encode a logical qubit $|x_L\rangle$ using the Steane code
* Simulate realistic Pauli errors on each physical qubit
* Measure stabilizer syndromes using ancilla qubits
* Perform conditional error correction
* Measure and decode the corrected logical qubit
* Analyze error correction performance via syndrome distribution and success rate


## How to Run

Make sure you have the following Python packages installed:

```bash
pip install qiskit matplotlib
```

Then run the script:

```bash
python steane_correction.py
```

You can modify:

* `x`: the input logical bit (0 or 1)
* `p`: error probability per qubit
* `shots`: number of repetitions
