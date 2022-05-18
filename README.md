In this exercise, you can analyze the impact of the MO-TRNG parameters on blackbox statistical tests.

You can launch the Python application and observe how the duty cycle, the variance and the accumulation time affect the results of the 5 black box tests included in the AIS31 test suite (four of which are also included in the FIPS 140-1).

Your goal is to find the the smallest <img src="https://render.githubusercontent.com/render/math?math=D"> for which the generated data would pass all five black box tests.

You should repeat the procedure for all possible <img src="https://render.githubusercontent.com/render/math?math=\frac{\sigma_{tot}}{T_{1}}"> and <img src="https://render.githubusercontent.com/render/math?math=N"> values.

<p><a href="https://mybinder.org/v2/gh/patrickhaddadteaching/TRNG_ex1/main?urlpath=voila%2Frender%2FTRNG_ex1_nb.ipynb" target="_blank" rel="noopener noreferrer">  <img src="ex1.png" width="50%" height="50%"></a></p>
