# Learning Better Physics: A Machine Learning Approach to Lattice Gauge Theory

## Info
Author: Sam Foreman

Submitted in partial fufillment of the requirements for the Doctor of
Philosophy degree in Physics in the Graduate College of The University of Iowa

August 2019

Thesis Supervisor: Yannick Meurice

## Abstract
In this work we explore how lattice gauge theory stands to benefit from new
developments in machine learning, and look at two specific examples that
illustrate this point.
%
We begin with a brief overview of selected topics in machine learning for those
who may be unfamiliar, and provide a simple example that helps to show how
these ideas are carried out in practice.

After providing the relevant background information, we then introduce an
example of renormalization group (RG) transformations, inspired by the tensor
RG, that can be used for arbitrary image sets, and look at applying this idea
to equilibrium configurations of the two-dimensional Ising model.

The second main idea presented in this thesis involves using machine learning
to improve the efficiency of Markov Chain Monte Carlo (MCMC) methods.
%
Explicitly, we describe a new technique for performing Hamiltonian Monte Carlo
(HMC) simulations using an alternative leapfrog integrator that is
parameterized by weights in a neural network.
%
This work is based on the L2HMC [`Learning to Hamiltonian Monte
Carlo'](https://arxiv.org/abs/1711.09268)
algorithm.

