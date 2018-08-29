# IPython/Jupyter Workshop at the NGCM Summer Academy

adapted from [ngcm summer academy](http://ngcm.soton.ac.uk/summer-academy/programme.html)



## Course content

- Introduction to IPython and Jupyter
- Tour of JupyterLab
- Exploring IPython
- Visualizing data in Jupyter
- interactivity with ipywidgets

Jupyter and IPython provide tools for interactive and parallel computing that are
widely used in scientific computing. We will show some uses of IPython
for scientific applications, focusing on exciting recent developments,
web-based notebooks with code, graphics, and rich HTML.


## Software Requirements

-   Python 3.x
-   Jupyter, including the Notebook and IPython. It should
    be available through the usual distribution channels, such as
    [Anaconda](http://continuum.io/downloads).
-   Your favorite text editor.
-   If you have trouble installing Anaconda, [this blog
    entry](http://www.southampton.ac.uk/~fangohr/blog/installation-of-python-spyder-numpy-sympy-scipy-pytest-matplotlib-via-anaconda.html)
    may help.
-   For the material related to `nbconvert`, the `pandoc` package, together with a  `latex` installation, would be useful.

To install the packages required for this course and the Pandas course
in a new environment with Anaconda, run:

```bash
conda create -n simula-workshop python=3 numpy scipy jupyter jupyterlab ipywidgets pandas matplotlib requests nbdime altair cython
```

Then, to use this environment, enter:

```bash
conda activate simula-workshop
```
