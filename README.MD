In this exercise, you can analyze the impact of input parameters of the EO-TRNG on the generator output. 

You can launch the application and observe how the duty cycle, the jitter variance, and the accumulation time affect the randomness of the generated numbers. 

Randomness is analyzed by observing the distribution and the auto-correlation of generated 4-bit bit-vectors.

Note: In the case of an ideal RNG, the distribution and the auto-correlation are in 99.9~\% of the cases between the red lines.

Your goal is to find the the smallest $D$ for which the EO-TRNG would not be distinguishable from an ideal RNG.

You should repeat the procedure for all possible $\frac{\sigma_{tot}}{T_{1}}$ and $\alpha_{1}$ values.
