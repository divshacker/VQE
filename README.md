# Variational Quantum Eigen Solver
A project on VQE done during Quantum Global Summer school 2020.

![Ideal_2](https://user-images.githubusercontent.com/55018955/132996672-e0709fa7-0283-43f5-8338-79bf72d3c77c.jpeg)

![Ideal_1](https://user-images.githubusercontent.com/55018955/132996694-04eb3dc4-e95c-41ca-9407-f01e5febc5a3.jpeg)
## Chemical Accuracy of Output
Chemical accuracy : error < 0.2 Ha. with UCCSD 

error< 0.02 Ha with RY ansatz.

## Implemented Classical Optimizer Parameters
VQE energy:

SLSQP: Tolerance = 0.01,  no. of iterations for =10 

Optimization convergence:

SLSQP: maximum no. of iterations=100

COBYLA: maximum no. of iterations=1000

LBFGS: maximum no. of iterations=15000

## Implemented Initial State Parameters 

Initial parameters: All set to zero

## Implemented Parameterized Circuit Parameters 

VQE calculations: UCCSD ( reps=1)

Optimization convergence: RY (depth=3) 

initial state= Hartree fock for both

## Implemented Simulation Backend Parameters 

No. of shots=100

noise model = IBM vigo

![opt_noise_final](https://user-images.githubusercontent.com/55018955/132996781-712e9d8d-7a10-4942-8e96-5c3bd2b78b7f.png)

![image-asset](https://user-images.githubusercontent.com/55018955/132996792-b8ce5544-9470-4c4d-94dc-444a29e42a87.png)






