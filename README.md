💻 Quantum Computing with Qiskit – Summer of Code 2025
By Nikhila Pothamsetty GitHub Repo: qml-soc-25

This repository documents my learning journey through foundational quantum computing algorithms, simulations, and circuit implementations using Qiskit, as part of the Summer of Code 2025. Over the past few weeks, I’ve explored key quantum computing concepts by writing and simulating quantum circuits, building both theoretical understanding and practical skills in quantum programming.

🌱 What I’ve Learned
🧠 1. Qubit Superposition
Files: superposition_1q.py, superposition_2q.py
I began with single- and two-qubit circuits applying Hadamard gates to create quantum superpositions.
Observed how qubits, unlike classical bits, can exist in a combination of 0 and 1, resulting in probabilistic outcomes.
Learned about measurement collapsing the state, and how results reflect the underlying quantum state vector.
🔍 2. Grover’s Search Algorithm
File: grover_algo.py
Built a two-qubit version of Grover’s Algorithm to find a marked item using fewer steps than classical search.
Designed a simple oracle and implemented inversion about the mean, which amplifies the target state’s probability.
Gained a practical understanding of amplitude amplification and its advantage in unstructured search problems.
🤖 3. Deutsch–Jozsa Algorithm (2 Implementations)
Files: deutsch_jozsa.py, deutsch_jozsa_random_oracle.py

Learned how quantum algorithms can provide exponential speedup over classical ones for specific problems.

Implemented both:

A static oracle version using cz gate (manually built for a balanced function).
A dynamic oracle generator that simulates constant/balanced oracles using binary patterns and controlled gates.
Understood how entanglement and interference are leveraged to eliminate multiple possibilities in a single shot.

⏳ 4. Phase Estimation Algorithm
File: phase_estimation.py
Explored the quantum phase estimation algorithm, a key building block in Shor’s algorithm and quantum simulations.
Learned how to construct controlled-unitary operations, apply inverse QFT, and interpret measured output as an estimate of a phase (eigenvalue).
This deepened my understanding of the role of eigenstates, unitary operators, and their phase relationships in quantum systems.
🎵 5. Quantum Fourier Transform (QFT)
File: quantum_fourier.py
Manually implemented the QFT on a 3-qubit register, including Hadamard, controlled-phase gates, and qubit swaps.
Understood the mathematical transformation from time domain to frequency domain in the quantum sense.
QFT is essential for many algorithms like Shor’s factoring and solving systems of linear equations in quantum computing.
📡 6. Quantum Teleportation Protocol
File: quantum_teleportation.py
Created a complete quantum teleportation circuit where an unknown quantum state is transferred from one qubit to another without physically moving the qubit itself.
Built entangled Bell pairs, performed Bell basis measurement, and applied conditional corrections based on classical bits.
Reinforced concepts of entanglement, quantum information transfer, and hybrid classical-quantum control.
🛠 Technologies Used
🧪 Qiskit – IBM's quantum computing SDK for building and simulating circuits
🐍 Python – Language used to script and run simulations
🖥 QASM Simulator (Aer) – Used to simulate quantum circuits on classical machines
📄 Jupyter Notebooks / .py Scripts – Code organization and testing
📁 Folder Structure (Recommended)
qml-soc-25/
├── bell_state.py                      # Bell pair preparation
├── deutsch_jozsa.py                   # Static oracle
├── deutsch_jozsa_random_oracle.py     # Dynamic oracle with randomness
├── grover_algo.py                     # Grover's search circuit
├── phase_estimation.py                # Phase estimation circuit
├── quantum_fourier.py                 # Manual QFT
├── quantum_teleportation.py           # Full teleportation protocol
├── superposition_1q.py                # 1-qubit superposition
├── superposition_2q.py                # 2-qubit Hadamard superposition
├── README.md                          # This file
📌 Key Takeaways
Quantum computing is non-intuitive, but hands-on simulation with Qiskit made it accessible.

Writing and testing quantum circuits helped me internalize abstract math concepts like tensor products, eigenvalues, interference, and unitary operations.

I've gained a strong foundation in core quantum algorithms that will help me explore advanced topics like:

Shor’s algorithm
Variational Quantum Eigensolvers (VQE)
Quantum Machine Learning (QML)
Hybrid quantum-classical circuits
✨ Next Steps
Explore IBM Quantum Lab to run circuits on real quantum hardware.
Learn about quantum error correction and noise models.
Dive into QML (Quantum Machine Learning) using qiskit-machine-learning.
