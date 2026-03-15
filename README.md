# STM32-Based-MultiChannelAnalyzer

This repository contains the single-channel version of the analog
frontend designed to insert into stm32f407 discovery board and can be used for alpha and gamma spectroscopy. Also repository contains code for stm32cubeide which can be uploaded into microcontroller.

Purpose and Applications

This project provides a compact STM32-based multichannel analyzer (MCA) and analog signal processing board designed for radiation spectroscopy and nuclear instrumentation experiments.

The system processes detector pulses using an analog frontend (spectrometric amplifier, comparator, and peak detector) and digitizes pulse amplitudes using the STM32 microcontroller ADC. The resulting pulse height data are transferred to a PC where energy spectra and coincidence matrices can be analyzed.

The system can be used with several types of radiation detectors, including:
 
 silicon detectors for charged particle spectroscopy

scintillation detectors such as CsI(Tl) or NaI(Tl)

photomultiplier tubes (PMT) or silicon photomultipliers (SiPM)

The analog front-end converts detector signals into shaped pulses suitable for digital acquisition and spectral analysis.

For data acquisition here we use developed by open gamma project team https://github.com/OpenGammaProject/Gamma-MCA web gamma mca open source programm.


Note: Comparator output also should be wired to PB3 pin.




