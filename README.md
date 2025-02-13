# Boson Sampling Simulation

This repository contains a Python implementation of a Boson Sampling simulation using the Strawberry Fields library. Boson Sampling is a quantum computational task that demonstrates quantum advantage by sampling from the output distribution of a linear optical network.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Dependencies](#dependencies)
- [License](#license)

## Introduction

Boson Sampling is a non-universal quantum computing model that is believed to be hard to simulate classically. This project simulates a simple Boson Sampling experiment using the Strawberry Fields library, which is a Python library for simulating continuous-variable quantum circuits.

The simulation involves:
- Preparing input Fock states.
- Applying rotation and beamsplitter gates.
- Calculating the joint Fock state probabilities.
- Comparing the results with theoretical predictions.
  
 ## Results
The simulation calculates the joint Fock state probabilities for a given input state and compares them with the theoretical values obtained using the permanent of the unitary matrix. The results are printed to the console, showing the probabilities and the percentage difference between the simulated and theoretical values.

## Dependencies
Strawberry Fields: A Python library for simulating continuous-variable quantum circuits.

NumPy: A fundamental package for scientific computing with Python.

The Walrus: A library for computing hafnians, permanents, and torontonians.

## Installation

To run this project, you need to have Python installed along with the required libraries. You can install the dependencies using the following commands:

```bash
pip install strawberryfields --upgrade
pip install xanadu-cloud-client
pip install numpy
pip install thewalrus
