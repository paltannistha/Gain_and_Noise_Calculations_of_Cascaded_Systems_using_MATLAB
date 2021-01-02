# Gain_and_Noise_Calculations_of_Cascaded_Systems_using_MATLAB

## Overview
Parameters like Noise, Signal-to-Noise Ratio(SNR) and Gain play an important role in the performance of communication systems. In this project, MATLAB(Matrix Laboratory) software is used to calculate these terms with the proper explanation.
## Goals
1. Calculation of **TOTAL GAIN**
2. Calculation of **TOTAL NOISE FIGURE**
3. Calculation of **TOTAL NOISE TEMPERATURE**
## Theory
Gain, Noise Figure and Noise Temperature allow us to characterize the noise performance of any communication system.

**Gain** -  Gain is a measure of the ability of a circuit (often an amplifier) to increase the power or amplitude of a signal from the input to the output.

**Noise** - Noise can be defined as any unwanted signals, random or deterministic, which interfere with the faithful reproduction of the desired signal in a system. It deteriorates the quality of the received signal (in case of analog systems) and degrades the throughput (in case of digital systems). Therefore it is important to maximise Signal-to-Noise Ratio (SNR) in a communication system.

**Noise Figure** - Noise Figure(NF )is simply the logarithmic scale equivalent of Noise Factor, expressed in decibels (dB).
Noise Factor provides a way to measure the additional noise added to a signal as it passes through a component. The Noise Factor (Fn) is a measure of the degradation of the SNR.
In cascaded systems, Total Noise Factor(Fn )depends upon the gain and  of each block (or stage). For example, in the case of amplifiers connected in cascade, each amplifier will add its own noise. Hence the overall noise factor will be due to the contribution by each amplifier.

**Noise Temperature** - Noise temperature is used to express the level of available noise power introduced by a component or source. Noise Temperature of a component describes the additional noise that the component inserts onto a signal before it is amplified.


## Software Program:
In this project, MATLAB software is used to design a calculator for the calculation of Total Gain, Total Noise Figure and Total Noise Temperature. Such types of calculators can be created with the array and matrix properties of MATLAB, and can be used for any cascade system with any number of stages. Coding is developed by using commands from MATLAB library.

Total Gain, Total Noise Figure and Total Noise Temperature are calculated using **Friis’s formula**.




