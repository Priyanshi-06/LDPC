# LDPC
# LDPC Coding and Decoding for 5G NR (Base Graph 2)
<p>This repository contains a MATLAB implementation of LDPC (Low-Density Parity-Check) coding and decoding for 5G New Radio (NR) based on Base Graph 2 (BG2), as specified in the 3GPP TS 38.212 standard.</p>

#Features
LDPC Matrix Construction
Implements LDPC parity-check matrix based on 5G NR Base Graph 2.
Uses a fixed lifting size of z = 52.
Expansion via circular permutation matrices derived from base graph indices.

#Encoding
Parity bits generated using matrix operations and cyclic shifts.

#Modulation and Channel Model
Modulation: BPSK (Binary Phase Shift Keying).
Channel: AWGN (Additive White Gaussian Noise).

#Decoding Algorithms
Soft-decision decoding using the Min-Sum Algorithm.
Performance compared with:
Hard-decision decoding (bit-flipping algorithm).
Normal approximation bound.
Shannon limit for theoretical reference.

#Performance Evaluation
Simulates decoding over a range of SNR values.
Evaluates bit error rate (BER) or decoding error probability.
Supports comparison across different code rates using the same base graph and lifting size.
