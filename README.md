In this exercise, you can analyze the impact of input parameters of the EO-TRNG on the generator output. 

You can launch the application and observe how the duty cycle, the jitter variance, and the accumulation time affect the randomness of the generated numbers. 
By checking the box, you can save the generated bits in a local file.

Randomness is analyzed by observing the distribution and the auto-correlation of generated 4-bit bit-vectors.

Your goal is to find the highest throuput (i.e. lowest $D$) for which the EO-TRNG would not be distinguishable from an ideal RNG.
In the case of an ideal RNG, the distribution and the auto-correlation are in 99.9\% of the cases between the red lines.

## How to launch the exercise ?
* We can execute this exercise on [Colab](https://colab.research.google.com/github/patrickhaddadteaching/TRNG_ex1/blob/main/TRNG_ex1_nb.ipynb)
    * Then press Ctrl+F9 or click on Runtime/Run All
* The exercise is a jupyter notebook compatible with voila.
The following libraries are required:
    * numpy
    * matplotlib
## Examples of procedures to execute the exercise with different systems.
1. Windows
    * First of all, Let clone this repositorie
    ```
     git clone https://github.com/patrickhaddadteaching/TRNG_ex1
    ```
    * [Download and install the latest Miniconda](https://docs.conda.io/en/latest/miniconda.html#latest-miniconda-installer-links).
    * Open the Anaconda Powershell Prompt associated to Miniconda3 and type the following commands to install  to install all the dependencies required by this exercise.
     ```
        conda install jupyter
        conda install numpy
        conda install matplotlib
        conda install -c conda-forge voila    
    ```
    * Now, you can either launch the notebook by executing the folowing command in the directory where you cloned this repositorie.
    ```
    jupyter-notebook.exe .\TRNG_ex1_nb.ipynb
    ```
    
    * Or, you can directly launch it with voila  by executing the folowing command in the directory where you cloned this repositorie.
    ```
    voila.exe .\TRNG_ex1_nb.ipynb
    ```
2. Linux
3. Mac OS X
