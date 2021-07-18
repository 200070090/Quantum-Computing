# Quantum-Computing-SoC-2021
# Summary of Learning:
## Introduction to Quantum Computing
We began with some general ideas and impact of Quantum Computing. Then some basic elements of QC like the qubit and related ideas like dirac notation, bloch spheres and superposition were introduced. First we dealt with single qubit and then multiqubit systems where we looked at entanglement, the bell state of a qubit pair serving as an example. We also noticed how the dimension of state space grows exponentially with number of qubits. Then we looked at the fundamental element of quantum circuits-quantum gates. We learnt how both single and multiple qubit gates are unitary operators and looked at some important gates like X, Y, Z, H, CNOT and others. Then we looked at measurements-another element of quantum circuits. 

We discussed some general problems and solutions which would be expanded upon later like the no cloning theorem, bell states and quantum teleportation. We discussed the fundamental ideas used in Quantum Algorithms like quantum parallelism and measurements, as well as learnt Deutsch and Deutsch Jozsa Algorithms as some good examples. Finally we had a brief overview of the various famous algorithms like algos based on Quantum Fourier Transform, search algorithms and others which we would learn in detail later. 
## Introductory Quantum Mechanics 
We built upon the fundamental mathematical concepts and theorems from linear algebra on vector spaces, bases, linear operators, inner products which can define an inner product space, eigenvectors and eigenvalues, adjoints, hermetian and unitary operators alongwith theorems on normal operators, tensor products-which are used to define multiqubit states in terms of single qubit states, polar and singular value decomposition.

Then we moved on to postulates of Quantum Mechanics where we looked at the state space-the vector space of quantum states, time evolution of quantum states which involves a unitary operator- the propagator, and the Schrodinger equation, and also postulates on measurements in Quantum Mechanics. Under Quantum measurements, we looked at measurement operators, their completeness relation and the probabilities associated with measurement. Next we looked at the problem of distinguishing quantum states and learnt that we cannot reliably distinguish non-orthogonal states. Then we dived deeper into measurements and looked at the particular subset of projective measurements, which are the typical measurements that are learnt in physics, as well as POVM measurements.
## Quantum Circuits
We looked at single qubit gates in much more detail. We learnt about various standard single qubit gates (S,T,etc) and rotation operators Like Rx, Ry, Rz, Rn and proved various useful algebraic identities relating these various gates. We learnt about controlled operations and gates like the Toffoli and gates with multiple control qubits and their implementation. There were interesting exercises in the material that helped understand the ideas better. Then we looked at measurements in Quantum circuits in greater detail and learnt about the principle of deferred measurements and how classically conditioned operators can be replaced by quantum conditioned operators, as well as the principle of implicit measurement. We also looked at measurements in different bases.

Then we learnt about universality of quantum gates, i.e, all gates can be approximated to arbitrary accuracy using composition of specific (finite) set of quantum gates. First we showed any multiqubit gate can be constructed exactly using CNOT and single qubit gates. Then we showed that a single qubit gate can be approximated to arbitrary accuracy using just the H and T gates by using ideas of rotation. We also looked at the error and the complexity of gates that would be required to approximate the given gate. We concluded after briefly looking at some relevant areas like Quantum simulations.
## Quantum Fourier Transform
The Quantum Fourier Transform plays a vital role in many algorithms, which were covered in this topic. First we learn about the QFT and came up with a quantum algorithm to implement it on a system of qubits, where a useful idea was to decompose the QFT of a basis state as a tensor product of single qubit states. 

Then we learnt about the phase estimation algorithm where we found how to estimate the phase of the eigenvalue of a unitary operator U, where the eigenvector was given. This utilised repeated use of controlled U operator followed by an inverse QFT and measurement to obtain an estimate of the phase. We also looked at how many qubit register would be needed to obtain an estimation to a given accuracy.

Next we looked at the order finding algorithm, which had direct application in Shor's factoring algorithm (massively faster than classical factorisation algos). The quantum part of Shor's algorithm was essentially just the order finding sub-routine.

We also looked at some other applications of QFT such as period finding and discrete logarithms before concluding this topic.
## Implementation through code
We learnt Q# and Qiskit from online sources like jupyter notebooks, which provided plenty practice problems and also taught us how to implement several algorithms in these languages. Some of these algorithms implemented by me in jupyter notebooks are given on this repository. They can be properly rendered using the following links.

1. [Quantum Teleportation](http://localhost:8889/notebooks/Quantum%20Teleportation.ipynb)
1. [Quantum Fourier Transform](http://localhost:8889/notebooks/Quantum%20Fourier%20Transform.ipynb)
1. [Phase Estimation](http://localhost:8889/notebooks/Phase%20Estimation.ipynb)
1. [Bernstein-Vazirani Algorithm](http://localhost:8889/notebooks/Bernstein-Vazirani%20Algorithm.ipynb)
1. [Superdense Coding](http://localhost:8889/notebooks/Superdense%20Coding.ipynb)
