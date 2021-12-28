# ML4SCI NMR Challenge 1st Place Solution

**Machine Learning for Science (ML4SCI) 2021 Hackathon Competition** was a competition which took place from **November 8-22, 2021** focusing on applying machine learning techniques to scientific challenges, including those from the fields of physics, astronomy and planetary science. The competition was open to anyone around the world.

There were six main challenges:

* Higgs Boson Challenge (Classification, General)
* Particle Images Challenge (Classification, Computer Vision)
* Strong Lensing Challenge (Multi-class Classification, Regression, Computer Vision)
* **NMR Spin Challenge (Multi-Target Regression)**
* Planetary Albedo (Regression, Image Analysis)
* Circumgalactic Medium (Dimensionality Reduction, Spectra)

### Background

Nuclear Magnetic Resonance (NMR) is an experimental technique that allows for the control and measurement of nuclear spins in crystals and molecules.
A common "recipe" for NMR is called the spin echo: the spins start aligned, begin to disperse, and are then refocused. This creates a sharp peak, or "echo", in the net magnetization M of the material at a later time. When the spins interact with each other, this refocused echo can become highly distorted.
Materials with strong electron-electron couplings have a variety of applications, from superconductivity to ferromagnetism. They also tend to enhance the nuclear spin-spin couplings, allowing NMR to act as a probe of these important systems.

### Problem Statement

Design and train a model that predicts the strength (<img src="https://latex.codecogs.com/svg.image?\alpha_x,&space;\alpha_z" title="\alpha_x, \alpha_z" />) and shape of interactions between the nuclear spins (<img src="https://latex.codecogs.com/svg.image?\theta" title="\theta" />) from simulated time-dependent magnetization curves, <img src="https://latex.codecogs.com/svg.image?M_x(t)\&space;\&\&space;M_y(t)" title="M_x(t)\ \&\ M_y(t)" />.

More details about the problem, data and metrics used refer to this [link](https://github.com/ML4SCI/ML4SCIHackathon/tree/main/NMRSpinChallenge).