# LDPC Coding and Decoding for 5G NR (Base Graph 2)
<p>This repository contains a MATLAB implementation of LDPC (Low-Density Parity-Check) coding and decoding for 5G New Radio (NR) based on Base Graph 2 (BG2), as specified in the 3GPP TS 38.212 standard.</p>

<h1>Features</h1>
<ul>
<li>LDPC Matrix Construction</li>
<li>Implements LDPC parity-check matrix based on 5G NR Base Graph 2.</li>
<li>Uses a fixed lifting size of z = 52.</li>
<li>Expansion via circular permutation matrices derived from base graph indices.</li>
</ul>

<h1>Encoding</h1>
<ul><li>Parity bits generated using matrix operations and cyclic shifts.</li></ul>

<h1>Modulation and Channel Model</h1>
<h2>Modulation:</h2> BPSK (Binary Phase Shift Keying).
<h2>Channel</h2>: AWGN (Additive White Gaussian Noise).

<h1>Decoding Algorithms</h1>
<ul>
<li>Soft-decision decoding using the Min-Sum Algorithm.</li>
<ul>Performance compared with:
<li>Hard-decision decoding (bit-flipping algorithm).</li>
<li>Normal approximation bound.</li>
<li>Shannon limit for theoretical reference.</li>
</ul>
</ul>

<h1>Performance Evaluation</h1>
<ul>
<li>Simulates decoding over a range of SNR values.</li>
<li>Evaluates bit error rate (BER) or decoding error probability.</li>
<li>Supports comparison across different code rates using the same base graph and lifting size.</li>
</ul>
