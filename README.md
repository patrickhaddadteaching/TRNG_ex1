In this exercise, you can analyze the impact of input parameters of the EO-TRNG on the generator output. 

You can launch the application and observe how the duty cycle, the jitter variance, and the accumulation time affect the randomness of the generated numbers. 
By checking the box, you can save the generated bits in a local file.

Randomness is analyzed by observing the distribution and the auto-correlation of generated 4-bit bit-vectors.

Your goal is to find the the smallest $D$ for which the EO-TRNG would not be distinguishable from an ideal RNG.
In the case of an ideal RNG, the distribution and the auto-correlation are in 99.9\% of the cases between the red lines.

You should repeat the procedure for all possible $\frac{\sigma_{tot}}{T_{1}}$ and $\alpha_{1}$ values.





## How to launch the exercise ?
The exercise is a jupyter notebook compatible with voila.
The following libraries are required:
* numpy
* h5py
* matplotlib
## Examples of procedures to execute the exercise with different systems.
1. Windows
    * First of all, Let clone this repositorie
    ```
     git clone https://github.com/patrickhaddadteaching/TRNG_ex1
    ```
    * [Download and install the latest Miniconda](https://docs.conda.io/en/latest/miniconda.html#latest-miniconda-installer-links).
    * Open the Anaconda Powershell Prompt associated to Miniconda3, set directory where you cloned this repositorie the working one and type the following commands to install  to install an isolated environment (named `env_exo_1`) of Python containing all the dependencies required by this exercise.
     ```
     conda create -p ./env_exo_1 python=3.6.9        
     conda install -p ./env_exo_1 -c conda-forge voila>=0.1.8
     conda install -p ./env_exo_1 jupyter numpy h5py matplotlib
    ```
    
    * Now, activate your 'env_exo_1' environment - you will need to do this before running the exercise.
    ```
    source activate -p ./env_exo_1
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
