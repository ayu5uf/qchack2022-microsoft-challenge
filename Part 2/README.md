# Free Form Challenge - Quantum Image processing 

## Introduction
This program utilises the Flexible Representation of Quantum Images (also known as [FRQI](https://qiskit.org/textbook/ch-applications/image-processing-frqi-neqr.html))  A greyscale checkerboard image is encoded, then rotations and translations of the image matrix are processed.

## Prerequisites
* [Microsoft Azure QDK](https://docs.microsoft.com/en-gb/azure/quantum/install-overview-qdk)

## Background info
Quantum Image Processing is an fast growing field within the quantum computing space, this project explores that field by encoding a simple 4x4 greyscale image that has been rotated and translated inside a 8x8 grid. 

## Results

![image](https://user-images.githubusercontent.com/84477843/162621091-1fd481c2-3831-4a28-9311-8039ab18c02f.png) - IONQ

![image](https://user-images.githubusercontent.com/84477843/162621089-0e2d74f6-da55-481d-8748-9d9cb723e62a.png) - Quantinium


![IONQ](https://user-images.githubusercontent.com/84477843/162621078-e65f4196-13af-4987-8ab2-b340788a0411.png) - IONQ.QPU




The first one is the perfect simulation of ionq; The second simulation is on the (slightly) noisy quantinuum device, and it is still good. The third run, on the ionq.qpu, is very noisy, but the image is still somewhat recognizable.
