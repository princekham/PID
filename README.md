# Notes on PID Control

<a href="https://drive.google.com/uc?export=view&id=1SeZoFNc3S8GLvmSFxOwjs5haiEFAcERr"><img src="https://drive.google.com/uc?export=view&id=1SeZoFNc3S8GLvmSFxOwjs5haiEFAcERr" style="width: 500px; max-width: 100%; height: auto" title="Click for the larger version." /></a>

- Laplace Transform takes a signal/system in the time-domain to it's complex frequency domain representation.
- It converts differential equations to algebraic equations, and convolution to multiplication <b> helps make analizing system easier</b>

<a href="https://drive.google.com/uc?export=view&id=1ZilSERnfjx48Ud-jg6zeYyWojkq7Yfe2"><img src="https://drive.google.com/uc?export=view&id=1ZilSERnfjx48Ud-jg6zeYyWojkq7Yfe2" style="width: 500px; max-width: 100%; height: auto" title="Click for the larger version." /></a>


<a href="https://drive.google.com/uc?export=view&id=1CDMPF1j7hP8LBmWW9ftJUBwGgqkscm3p"><img src="https://drive.google.com/uc?export=view&id=1CDMPF1j7hP8LBmWW9ftJUBwGgqkscm3p" style="width: 500px; max-width: 100%; height: auto" title="Click for the larger version." /></a>
<H6>Z Transform</H6>
- it is discrete version of Laplace Transform

<a href="https://drive.google.com/uc?export=view&id=14ZwIqBtcYBPHUDpeF0d_L-j4uizxeM_W"><img src="https://drive.google.com/uc?export=view&id=14ZwIqBtcYBPHUDpeF0d_L-j4uizxeM_W" style="width: 500px; max-width: 100%; height: auto" title="Click for the larger version." /></a>

<a href="https://drive.google.com/uc?export=view&id=1DYPGxzuROKStT_pGhRHTXez7ZF137QV_"><img src="https://drive.google.com/uc?export=view&id=1DYPGxzuROKStT_pGhRHTXez7ZF137QV_" style="width: 500px; max-width: 100%; height: auto" title="Click for the larger version." /></a>
- The C(z) function is just an example function.
<a href="https://drive.google.com/uc?export=view&id=1f4GwSMsfDKlLEssVjIftAPKDAYLp1D4R"><img src="https://drive.google.com/uc?export=view&id=1f4GwSMsfDKlLEssVjIftAPKDAYLp1D4R" style="width: 500px; max-width: 100%; height: auto" title="Click for the larger version." /></a>
- the last equation is the discrete version of the differential equation used to implement in microcontroller
-a anb b coefficient, if in differential equation case - resistors and capacitors values, if in discrete equation case - can be adjusted in the code.

<H6>Digital Control</H6>

<a href="https://drive.google.com/uc?export=view&id=1JqkryGc6QNPlJB9RgoFhe-k1S6fW3zEz"><img src="https://drive.google.com/uc?export=view&id=1JqkryGc6QNPlJB9RgoFhe-k1S6fW3zEz" style="width: 500px; max-width: 100%; height: auto" title="Click for the larger version." /></a>


<a href="https://drive.google.com/uc?export=view&id=1Uz60VVrOf4QnQ9PrxnkHiIVmh3R_z1X4"><img src="https://drive.google.com/uc?export=view&id=1Uz60VVrOf4QnQ9PrxnkHiIVmh3R_z1X4" style="width: 500px; max-width: 100%; height: auto" title="Click for the larger version." /></a>
- We have to convert C(S) to C(z) such that its frequency response mataches is C(s) frequency response.

<a href="https://drive.google.com/uc?export=view&id=10JV8YhPJFpzeQinigbwoSCgYrVJXTROm"><img src="https://drive.google.com/uc?export=view&id=10JV8YhPJFpzeQinigbwoSCgYrVJXTROm" style="width: 500px; max-width: 100%; height: auto" title="Click for the larger version." /></a>

<b>Approximation method used:</b>


<a href="https://drive.google.com/uc?export=view&id=1-96CQdub63ma0n7XfmhVsVTDnCSyz7QM"><img src="https://drive.google.com/uc?export=view&id=1-96CQdub63ma0n7XfmhVsVTDnCSyz7QM" style="width: 500px; max-width: 100%; height: auto" title="Click for the larger version." /></a>

