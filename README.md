# Adaptive Modulation Simulator

An interactive, single-page simulator for an Adaptive Modulation Selection 
project in mobile wireless communication.

## What it does
Simulates how a mobile device's channel quality (SNR) changes as it moves, 
and how an adaptive system responds by switching modulation schemes 
(BPSK → QPSK → 16/64-QAM) to balance reliability vs. data rate.

## Features
- Three mobility scenarios: Pedestrian, Car, Train (each with a realistic 
  speed range you can adjust)
- Selectable carrier frequency (900 MHz to 26 GHz mmWave) — shows how 
  frequency affects Doppler shift and obstacle sensitivity
- Multiple obstacle types (tunnel, buildings, foliage, hills, interference) 
  that can be combined
- Live calculation trace: Doppler shift, path loss, shadowing, coherence 
  time, and instantaneous SNR, all computed and shown in real time
- SNR-vs-position and BER-vs-SNR charts
- Color-coded signal-flow diagram showing the live decision path

## Live demo
👉 **[https://deenaapawaskar.github.io/Adaptive-Modulation-Simulator/](https://deenaapawaskar.github.io/Adaptive-Modulation-Simulator/)**

## Built with
Plain HTML/CSS/JavaScript — no build step, no dependencies.
