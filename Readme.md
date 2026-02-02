# Computer Lab

## Mechanics for MSc in Engineering - Spring 2026

For details please see the **lab description** on [the course homepage](https://lms.oru.se/ultra/courses/_33469_1/outline).

## Setup instructions (computer room T203)

In the computer room T203 the computers have an installation of Python (v3.10) but in order to run the lab on the Windows computers in the computer room you will need to install a few extra Python packages. 

To do this open the Windows command line (CMD.exe) and use the `pip` command to install SciPy, Matplotlib, and jupyter-lab

```bash
pip install scipy matplotlib jupyter-lab
```

To start `jupyter-lab` run the `jupyter-lab.exe` file located in your folder

```bash
C:\Users\YourUserName\AppData\Roaming\Python\Python310\Scripts\jupyter-lab.exe
```

where `YourUserName` should be replaced with **your** ORU user name (i.e. the user name you use for logging in on the Windows computer).

Starting `jupyter-lab` on the command line should open up a new browser window with the `jupyter-lab` environment.

## Slide decks

Here are the interactive notebooks for the Lab sessions 2,3, and 4:

- [Lab session 2] Arrays and visualization [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/HugoStrand/mechanics_computer_lab_catenary/main?urlpath=%2Fdoc%2Ftree%2FArraysAndViz.ipynb)

- [Lab session 3] Numerical solution of boundary value problems [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/HugoStrand/mechanics_computer_lab_catenary/main?urlpath=%2Fdoc%2Ftree%2FNumericalBVPSolution.ipynb)

- [Lab session 4] Boundary condition fit for analyti solution [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/HugoStrand/mechanics_computer_lab_catenary/main?urlpath=%2Fdoc%2Ftree%2FBoundaryConditionFit.ipynb)
