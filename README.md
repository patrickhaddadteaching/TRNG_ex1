Repository for Ex1 of Embedded Cryptography Book Section 9.1

In this exercise, you can play with an EO-TRNG.
By scanning or clicking on the QR-code you can launch the application and observe how the duty cycle,the jitter variance and the accumulation time affect randomness of the generated numbers. 
The randomness is analyzed by observing the distribution and the auto-correlation of generated 4-bit bit-vectors.

Note: In the case of an ideal RNG, the distribution and the auto-correlation are in 99.9% cases between the red lines.

Your goal is to find the the smallest $D$, for which the EO-TRNG would not be distinguishable from an ideal RNG.
You should repeat the procedure for all possible $\frac{\sigma_{tot}}{T_{1}}$ and $\alpha_{1}$ values.


![image](https://raw.githubusercontent.com/patrickhaddadteaching/TRNG_ex1/main/ex1.png = 10x)

![](https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png | width=100)
