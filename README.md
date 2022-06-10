In this exercise, you can analyze the impact of input parameters of the EO-TRNG on the generator output. 

You can launch the application and observe how the duty cycle, the jitter variance, and the accumulation time affect the randomness of the generated numbers. 

Randomness is analyzed by observing the distribution and the auto-correlation of generated 4-bit bit-vectors.

Your goal is to find the the smallest $D$ for which the EO-TRNG would not be distinguishable from an ideal RNG.

You should repeat the procedure for all possible $\frac{\sigma_{tot}}{T_{1}}$ and $\alpha_{1}$ values.

Note: In the case of an ideal RNG, the distribution and the auto-correlation are in 99.9\% of the cases between the red lines.

## How to launch the exercise ?
The exercise is a jupyter notebook compatible with voila.
The following libraries are required:
* numpy
* h5py
* matplotlib
## Procedures to execute the exercise with different systems.
1. Windows
    * First of all, Let clone this repositorie
    ```
     git clone https://github.com/patrickhaddadteaching/TRNG_ex1
    ```
    * [Download and install the latest Miniconda](https://docs.conda.io/en/latest/miniconda.html#latest-miniconda-installer-links).
    * Open the Anaconda Powershell Prompt associated to Miniconda3 and type the following commands to install the required libraries.
     ```
        conda install jupyter
        conda install numpy
        conda install h5py
        conda install matplotlib
        conda install -c conda-forge voila
    ```
    * You can either launch the notebook by executing the folowing command in the directory where you cloned this repositorie.
    ```
        jupyter-notebook.exe .\TRNG_ex1_nb.ipynb
    ```
    * Or, you can directly launch it with voila  by executing the folowing command in the directory where you cloned this repositorie.
    ```
        voila.exe .\TRNG_ex1_nb.ipynb
    ```
2. Linux
3. Mac OS X
