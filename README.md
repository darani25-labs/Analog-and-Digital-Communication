# 📡 AM Sideband Power and Frequency Analysis Using MATLAB

## 📌 About

This repository contains the MATLAB implementation of **Experiment 1(b): Characteristics Study of Sideband Power and Frequencies in AM**.

The experiment demonstrates the generation and analysis of an **Amplitude Modulated (AM) signal** using MATLAB. It studies the message signal, carrier signal, AM signal, demodulated signal, sideband frequencies, and power distribution.

## 🎯 Objectives

- To generate an Amplitude Modulated (AM) signal using MATLAB.
- To determine the Upper Sideband (USB) and Lower Sideband (LSB) frequencies using frequency spectrum analysis.
- To calculate the carrier power and sideband power for a given modulation index.
- To analyze the effect of modulation index on sideband power distribution and transmission efficiency.

## ⚙️ Parameters Used

| Parameter | Value |
|---|---:|
| Message Amplitude (Am) | 1 |
| Message Frequency (fm) | 500 Hz |
| Carrier Amplitude (Ac) | 5 |
| Carrier Frequency (fc) | 5000 Hz |
| Sampling Frequency (fs) | 20 × fc |
| Modulation Index (μ) | 0.2 |

## 📚 Theory

Amplitude Modulation is a modulation technique in which the amplitude of a high-frequency carrier signal is varied according to the instantaneous amplitude of the message signal.

### AM Signal

AM signal:

` s(t) = Ac [1 + μ sin(2πfmt)] sin(2πfct) `

### Modulation Index

` μ = Am / Ac `

For the given parameters:

` μ = 1 / 5 = 0.2 `

### Sideband Frequencies

Upper Sideband (USB):

` fUSB = fc + fm `

Lower Sideband (LSB):

` fLSB = fc - fm `

### Carrier Power

` Pc = Ac² / 2 `

### Sideband Power

Power of each sideband:

` PSB = μ²Pc / 4 `

## 📊 Calculated Results

| Parameter | Result |
|---|---:|
| Modulation Index | 0.2 |
| Carrier Frequency | 5000 Hz |
| Upper Sideband Frequency | 5500 Hz |
| Lower Sideband Frequency | 4500 Hz |
| Carrier Power | 12.5 W |
| USB Power | 0.125 W |
| LSB Power | 0.125 W |

## 🔬 MATLAB Implementation

The MATLAB program performs the following operations:

1. Clears the MATLAB workspace and command window.
2. Defines the message and carrier signal parameters.
3. Generates the message signal.
4. Generates the carrier signal.
5. Calculates the modulation index.
6. Generates the AM signal.
7. Demodulates the AM signal using the Hilbert Transform.
8. Removes the DC component from the demodulated signal.
9. Performs FFT analysis of the AM signal.
10. Determines the USB and LSB frequencies.
11. Calculates carrier and sideband power.
12. Displays the results using MATLAB plots and command-window output.

## 📈 Output

The MATLAB simulation produces the following plots:

- Message Signal
- Carrier Signal
- AM Signal
- Demodulated Signal
- Sideband Frequency Spectrum
- Power Distribution

## 🧪 Signal Analysis

The frequency spectrum of the AM signal contains three major frequency components:

- Lower Sideband (LSB) = 4500 Hz
- Carrier = 5000 Hz
- Upper Sideband (USB) = 5500 Hz

The power distribution graph shows the carrier power and the power contained in the two sidebands.

## 🛠️ Tools Used

- MATLAB
- Fast Fourier Transform (FFT)
- Hilbert Transform
- Signal Processing

## 📂 Repository Contents

- MATLAB source code (`.m`)
- Experiment documentation (`.pdf`)
- Output graphs
- README documentation

## ✅ Result

The AM signal was successfully generated and analyzed using MATLAB. The Upper Sideband and Lower Sideband frequencies were identified using frequency spectrum analysis, and the carrier and sideband powers were calculated successfully.

## 👩‍💻 Experiment Details

**Subject:** Analog and Digital Communication

**Experiment No.:** 1(b)

**Experiment Title:** Characteristics Study of Sideband Power and Frequencies in AM Using MATLAB
