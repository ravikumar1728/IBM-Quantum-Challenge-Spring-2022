# IBM-Quantum-Challenge-Spring-2022
May 23 — May 28

The IBM Quantum Spring Challenge 2022 will be divided into two segments. One part will invite participants to tackle problems revolving around many-body systems, while the other will focus on fermionic chemistry simulations. Participants will get a one-of-a-kind opportunity to investigate problems at the forefront of quantum computing research.

Each exercise is presented as a Jupyter notebook which is hosted on the IBM Quantum Lab. Complete all parts in each to complete the exercise.


# Exercise 1

# Tight-binding model
How is studying electrons within a material similar to a cup of coffee going cold? How can a system have a 'memory' of it's original state, even after it's changed multiple times? The dynamics within what we refer to as Many-Body Systems help us understand all of this, and more. Exercise 1, 2, and 3 are all part of the same storyline that explores these questions through the lens of a quantum computer.

In exercise 1 we begin to understand how overlaps in the particle wavefunction with multiple lattice sites allow for particle transport within a tight-binding model. We also observe how the time needed for this to happen can change dramatically compared to classical transport. To execute this investigation on a quantum computer, we must decompose our math into a product of single and two-qubit gates that are native to the quantum computer. You will use a method called trotterization to simulate the dynamics of a particle in the tight-binding system.

# Exercise 2

# Quantum Random Walks and Localization
In a tight-binding system the particle propagation can be described by a continuous-time quantum random walk. Quantum random walks are the quantum mechanical analog of classical random walks. Quantum properties such as single-particle superposition and interference result in a qualitative difference between classical and quantum random walks. Therefore, quantum walks are quadraticaly faster than classical walks, which is analogous to the quadratic speed-up of the Grover search algorithm compared to classical search.

However, particle propagation is significantly impacted by the introduction of disorder in the site energies, leading to Anderson localization. Lattice inhomogeneity causes scattering and leads to quantum interference that tends to inhibit particle propagation, a signature of localization. The wavefunction of a localized particle rapidly decays away from its initial position, effectively confining the particle to a small region of the lattice.

# Exercise 3

# Many-body quantum dynamics
A closed quantum many-body system initialized in a non-equilibrium will reach the equilibrium state, refered to as thermalization, under its own dynamics. This behavior is as a result of the laws of statistical mechanics, and analogous to a hot cup of coffee cooling down to the surronding tempreture if left unattended. However, the presence of lattice disorder prevents the system from evolving into an egodic thermalized state. This interplay between disorder and particle interaction results in many-body localization (MBL), and it allows the system to retain a memory of its initial condition at all times.


# Exercise 4

# Using VQE On a Water Molecule

In Challenge 4 we will shift our gaze over to analyzing fermionic systems - like water! You will be using a well-known algorithm called the Variational Quantum Eigensolver (VQE) to attempt to find the ground state energy (lowest energy) of a water molecule. VQE has multiple aspects you need to understand, like how to define our problem with Qiskit Nature, how to select the most efficient ansatz, and how to use the ground state results to perform excited states calculations.
