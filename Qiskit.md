The qiskit SDK is an open source software development kit for working with quantum computers at the level of extended quantum circuits, operators, and primitives

The qiskit ecosystem is a collection of software and tutorials that build on or extend qiskit

qiskit runtime is a quantum computing service and programming model that allows users to optimize workloads and efficiently execute them on quantum systems at scale

qiskit primitives are the most basic building blocks used to build a quantum workflow, available through Runtime

[pyenv-win](https://github.com/pyenv-win/pyenv-win) : python version manager for windows

API token: ~~314288dc0e77459b155b7904b67e4a3410cac7ef3522cb64a0e29b9e41b6e395a67aa012a51e24fbbce44a5680990bf5280834593807fdf9a376bacdddc6064d~~

Qiskit circuits:
pattern workflow:
- map
- optimize
- execute
- post process

Map: How we start with a classical computer and figure out how to map it to a quantum computer

Optimize: Use qiskit's transpiler to route and layout the circuit to physical qubit hardware, convert to basis gates of the hardware, and reduce the number of operations

Execute:
use the qiskit runtime primitives to run your quantum circuits on quantum hardware

post-process:
process measurement data on a classical computer


### Project Ideas
- publish a paper
  - start reading papers such as, options pricing using quantum computers - IBM
  - image processing in quantum computers
  - [archive](https://arxiv.org/)
- Solve a game
  - QUBO algo
- contribute to open source quantum framework
  - qiskit camp githubs
  - [quantum opensource foundation](https://qosf.org/) 

### Primitives
- a _primitive_ is the smallest processing instruction, the simplest building block from which one can create something useful for a given abstraction level.
- The two most common tasks for quantum computers are sampling quantum states and calculating expectation values. These tasks motivated the design of the Qiskit primitives: **Estimator** and **Sampler**.
  - Estimator computes expectation values of observables with respect to states prepared by quantum circuits.
  - Sampler samples the output register from quantum circuit execution.