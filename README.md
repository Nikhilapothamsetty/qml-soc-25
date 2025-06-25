# 💻 Quantum Computing with Qiskit – Summer of Code 2025

*By Nikhila Pothamsetty*  
**GitHub Repo**: [qml-soc-25](https://github.com/nikhila2007-ux/qml-soc-25)

This repository documents my learning journey through foundational quantum computing algorithms, simulations, and circuit implementations using **Qiskit**, as part of the **Summer of Code 2025**. Over the past few weeks, I’ve explored key quantum computing concepts by writing and simulating quantum circuits, building both theoretical understanding and practical skills in quantum programming.

---

## 🌱 What I’ve Learned

### 🧠 1. **Qubit Superposition**

**Files**: `first working quantum circuit.py`, `2_qubit_superposition.py`

- Started with 1- and 2-qubit circuits using **Hadamard gates** to generate **quantum superpositions**.
- Observed probabilistic outcomes that demonstrate the **non-deterministic nature** of qubit states.
- Learned about **measurement collapse**, **circuit basics**, and how quantum data flows.

---

### 🧩 2. **Bell State and Entanglement**

**File**: `bell_state.py`

- Built a **Bell state** (|Φ⁺⟩) using `H` and `CX` gates.
- Understood **quantum entanglement** — how measurement of one qubit affects the other instantly.
- Visualized using **histograms** to confirm correlated outcomes like `00` and `11`.

---

### 🔍 3. **Grover’s Search Algorithm**

**File**: `grover_algo.py`

- Implemented a basic **Grover’s Algorithm** on 2 qubits to find a marked item.
- Used a simple **oracle** (`CZ` gate) and performed **inversion about the mean**.
- Observed how **amplitude amplification** improves search efficiency vs classical.

---

### ⚡ 4. **Deutsch–Jozsa Algorithm**

**File**: `deutsch_jozsa.py`

- Implemented a 2-qubit version of the **Deutsch–Jozsa Algorithm**.
- Used it to distinguish between **constant** and **balanced** functions in one quantum query.
- Learned how **interference and entanglement** eliminate possibilities before measurement.

---

### ⏳ 5. **Phase Estimation Algorithm**

**File**: `phase_estimation.py`

- Simulated the **Quantum Phase Estimation (QPE)** algorithm.
- Built circuits using **controlled unitary gates**, **Hadamards**, and **inverse QFT**.
- Estimated the phase (eigenvalue) of a known unitary and connected it with **Fourier analysis**.

---

### 🎵 6. **Quantum Fourier Transform (QFT)**

**File**: `quantum_fourier.py`

- Manually coded the **QFT** using Hadamards, controlled-phase gates, and swaps.
- Demonstrated how QFT transforms amplitudes from time to frequency domain.
- Deepened understanding of **interference** and **quantum parallelism**.

---

### 📡 7. **Quantum Teleportation Protocol**

**File**: `quantum_teleportation.py`

- Built a full **quantum teleportation** circuit transferring an unknown qubit state.
- Used **Bell state entanglement**, **Bell basis measurements**, and **classical correction**.
- Reinforced the concept of **quantum information transfer without physical movement**.

---

## 📁 Folder Structure

```plaintext
qml-soc-25/
├── first working quantum circuit.py        # 1-qubit superposition
├── 2_qubit_superposition.py               # 2-qubit superposition
├── bell_state.py                          # Bell state entanglement
├── deutsch_jozsa.py                       # Deutsch–Jozsa algorithm
├── grover_algo.py                         # Grover's search
├── phase_estimation.py                    # Phase estimation circuit
├── quantum_fourier.py                     # Manual QFT
├── quantum_teleportation.py               # Example of quantum teleportation showing how a qubit’s state is transferred
├── README.md                              # This file


