# Quantum Error Correction

## Obstacles to QEC
1. No-cloning theorem: You can't create a replica of an unkown quantum state using a universal Unitary transformation.
2. Measurements lead to collapse of the quantum states.
3. Quantum Noise: Quantum errors form a continuous set (classical errors are discrete).

<details>
  <summary><b>Eigen-States of an operator form it's basis states</b></summary>
  In quantum mechanics, the eigenstates of a Hermitian operator (such as the Hamiltonian, spin operators, or position/momentum operators) form a set of orthogonal states. Since Hermitian operators correspond to observables, their eigenstates have real eigenvalues and can be used to define measurement outcomes.
  These orthogonal eigenstates span the Hilbert space, meaning any quantum state in that space can be expressed as a linear combination (or superposition) of the operator's eigenstates.
</details>

## Work-arounds for the Obstacles
1. Instead of copying the quantum information (we can't because of the no-cloning theorem), we have encoded the quantum information into a subspace.
2. We avoid the fact that measurements disturb a quantum system by performing measurements that project onto subspaces.
3. 
