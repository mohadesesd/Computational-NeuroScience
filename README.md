# Computational NeuroScience Master Course Series 2020

## About the Course

The Computational Neuroscience course delves into the intricate modeling of neural processes and the simulation of neural systems. It is designed to provide students with hands-on experience in computational techniques for understanding the complexities of the nervous system.

## Projects Overview

This repository is structured into several key sections, each representing a fundamental area of study within the field of computational neuroscience:

### Neuron Models

- **Leaky Integrate-and-Fire (LIF)**: Simulates the basic form of a neuron model that integrates incoming signals until a threshold is reached, resulting in a 'fire' (spike).
- **Exponential Leaky Integrate-and-Fire (ELIF)**: Expands upon the LIF model by incorporating an exponential term to the membrane potential equation, allowing for a more realistic firing dynamic.
- **Adaptive Exponential Leaky Integrate-and-Fire (AdaptiveELIF)**: Further extends the ELIF model by adding an adaptation mechanism, which introduces spike-frequency adaptation to the neuron's activity.

### Spiking Neural Network Framework

- **Neural Populations**: Represents groups of neurons that interact and process information collectively.
- **Synaptic Connections**: Simulates the complex network of synapses that form the connections between neurons, allowing for the transmission of signals within the network.

### Learning in SNNs

- **Spike-Timing-Dependent Plasticity (STDP)**: Implements a learning rule based on the timing of spikes that adjusts synaptic strengths for unsupervised learning.
- **Reinforcement STDP (rSTDP)**: Integrates reinforcement signals into the STDP framework, allowing the network to adjust its synapses in a reward-based learning context.

### Image Processing

- **Difference of Gaussians (DoG)**: Utilizes DoG filters to process images by highlighting edges and removing noise, mimicking the processing in the retina.
- **Gabor Filters**: Applies Gabor filters for texture and edge analysis in images, reflecting the image processing capabilities of simple cells in the visual cortex.

### Spiking Neural Network for Object Recognition

An implementation of a Spiking Neural Network (SNN) tailored for the task of object recognition using the CIFAR-10 dataset.

## Getting Started

To get started with the projects in this repository, please ensure you have the following prerequisites installed:

- Python 3.x
- Relevant Python libraries such as NumPy, Matplotlib, Pytorch, etc.

