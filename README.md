# Overview

### Motivation:
Our motivation with Poinsly is to gain a better understanding on how to make a programming language.

### Description:
Poinsly is a programming language made on Windows and using Python that helps to solve linear or quadratic equations similarly to a graphing calculator. It utilizes the SLY premade parser, lexer and interpreter. How it works is that you enter either a linear or quadratic equation like this
`1x^2+-5x+4` or `2x+24` and it would give you the result of said equation and a corresponding graph in a separate window.

### Requierements:
* Python 3.6 and higher
  * (optional: Anaconda)
  * (optional: Visual Studio Code)  

### Modules:
* SLY
* Cmath
* numpy
* matplotlib

## Hurdles and Future adjustments:
One of our largest hurdles was the losing a team member after needing to restructure Phase 2 of our project.
This meant we had to learn on how and what Poinsly was going to be in a short amount of time.

We hope to one day get to implement more ways to preform more actions past the simple Precalculus problems perhaps maybe integrals or derivatives. We also hope to solve the shift/reduce and reduce/reduce issues in the future as well.

### Installation:
After downloading `Poinsly.py` and Python, 
For VScode, enter this to create a virtual environment (replace directories with the folders Poinsly.py is in)
``` python -m venv C:\Directories\venv ```
after you do that use 
``` pip install Library ```
To install SLY, cmath, numpy and matplotlib (replace Library with any of the 4 modules written here)

(*Note: installation may vary when using different IDE's*)

### After installation:

After all of the installation is complete, you run the code through the terminal and then enter whichever quadratic or linear equation like the ones mentioned previously, anything different will grant differing results and errors. Once you do that you get the result and the corresponding graph should appear in a separate window, likely in the taskbar.

--------------------------------------------------------
[Explanation Video](https://youtu.be/XQJEUbpsRwc)
--------------------------------------------------------
[Anaconda](https://www.anaconda.com/products/individual)
--------------------------------------------------------
[SLY Documentation](https://sly.readthedocs.io/en/latest/index.html)
--------------------------------------------------------
