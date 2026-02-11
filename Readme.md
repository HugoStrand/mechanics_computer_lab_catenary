# Computer Lab

## Mechanics for MSc in Engineering - Spring 2026

For details please see the **lab description** on [the course homepage](https://lms.oru.se/ultra/courses/_33469_1/outline).

## Setup instructions (computer room T203)

In the computer room T203 the computers have an installation of Python (v3.10) but in order to run the lab on the Windows computers in the computer room you will need to install a few extra Python packages. 

To do this open the Windows command line (`CMD.exe`) and use the `pip` command to install SciPy, Matplotlib, and Jupyter Lab

```bash
pip install scipy 
pip install matplotlib
pip install jupyterlab
```

To start Jupyter Lab run the `jupyter-lab.exe` file located in the folder

```bash
C:\Users\YourUserName\AppData\Roaming\Python\Python310\Scripts\jupyter-lab.exe
```

where `YourUserName` should be replaced with **your** ORU user name (i.e. the user name you use for logging in on the Windows computer).

Starting `jupyter-lab` on the command line should open up a new browser window with the `jupyter-lab` environment.

Note that this procedure has to be repeated on each computer you use in the computer room.

## Alternative setups

If you have a Google account you can get access to a Jupyter environment directly in your browser using [Google Collab](https://colab.research.google.com/).

## Slide decks

Here are the interactive notebooks for the Lab sessions 2, 3, and 4:

- __Lab session 2:__ Arrays and visualization [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/HugoStrand/mechanics_computer_lab_catenary/main?urlpath=%2Fdoc%2Ftree%2FArraysAndViz.ipynb)

- __Lab session 3:__ Numerical solution of boundary value problems [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/HugoStrand/mechanics_computer_lab_catenary/main?urlpath=%2Fdoc%2Ftree%2FNumericalBVPSolution.ipynb)

- __Lab session 4:__ Boundary condition fit for analytic solution [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/HugoStrand/mechanics_computer_lab_catenary/main?urlpath=%2Fdoc%2Ftree%2FBoundaryConditionFit.ipynb)
