# RqPINN (SciML-QEP)

This repository contains codes of current state-of-the art SciML algorithms for solving quantum eigenvalue problems used in a project I’m conducting with Professor Antonio Herrera Martin. Even after completing my summer research, the project is still ongoing as I have extended it beyond just PINN, to include FNO's and self-attention matrix to obtain all eigenpairs at once (rather than training a separate neural network for each eigenpair, which was quite computationally expensive and we had to worry about issues like stability and convergence).

I am still not there yet, as the main goal of this work are two things: (1) To solve for higher dimensions where numerical techniques face significant challenges such as the curse-of-dimensionality. (2) To be able to consider potentials whose eigenpairs are very difficult to obtain numerically.

One major interesting aspect of this work is that we basically do not need data for the target variable (It is totally unsupervised! though, we can augment the approach with some target variable data if we want, but not necessarily). 

I will continue to update this repository as I move further in the project. And in the nearest future, I aim to include problems in fluid dynamics utilizing some algorithms that I will be developing, which can capture the physics of the considered problems, in addition to ensuring robustness and reliability through theoretical guarantees.
