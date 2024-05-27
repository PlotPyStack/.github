# PlotPyStack: A Toolkit for Scientific GUI-based Software in Python

## Overview

Welcome to PlotPyStack, a comprehensive toolkit designed to aid in the development of scientific GUI-based software using Python. This organization houses powerful packages, each providing unique functionalities aimed at simplifying data visualization, plotting, and GUI development for scientific applications.

🚀 *PlotPyStack is the result of 15 years of expertise in the development of scientific software using Python-Qt.*

The table below summarizes the packages included in the PlotPyStack organization:

| Package Logo | Package Name  | Creation date | Short Description                                                |
|--------------|---------------|---------------|---------------------------------------------------|
| ![PythonQwt Logo](https://raw.githubusercontent.com/PlotPyStack/.github/main/data/PythonQwt.png) | [PythonQwt](https://github.com/PlotPyStack/PythonQwt)    | 2014 | Low-level Qt plotting widgets for Python.   |
| ![guidata Logo](https://raw.githubusercontent.com/PlotPyStack/.github/main/data/guidata.png) | [guidata](https://github.com/PlotPyStack/guidata)      | 2009 | A Python library for easy dataset manipulation and display.      |
| ![guiqwt Logo](https://raw.githubusercontent.com/PlotPyStack/.github/main/data/guiqwt.png) | [guiqwt](https://github.com/PlotPyStack/guiqwt)       | 2009 | An efficient 2D data-plotting library based on PythonQwt (discontinued: replaced in 2023 by PlotPy). |
| ![plotpy Logo](https://raw.githubusercontent.com/PlotPyStack/.github/main/data/plotpy.png) | [plotpy](https://github.com/PlotPyStack/plotpy)       | 2016 | A high-level interface for creating a variety of plot types.     |

PythonQwt, guidata, guiqwt and plotpy were created by Pierre Raybaut and are now maintained by the PlotPyStack organization.

For more details about each package, please refer to their respective repositories.

## Details on stack packages

PlotPyStack is a Python-Qt visualization and scientific GUI stack based on PythonQwt, guidata and plotpy.

PlotPyStack is composed of the following packages:

* [PythonQwt](https://github.com/PlotPyStack/PythonQwt): Python implementation of the Qwt C++ library. The `PythonQwt` project was initiated to solve -at least temporarily- the obsolescence issue of `PyQwt` (the Python-Qwt C++ bindings library) which is no longer maintained. The idea was to translate the original Qwt C++ code to Python and then to optimize some parts of the code by writing new modules based on NumPy and other libraries.

* [guidata](https://github.com/PlotPyStack/guidata): Automatic graphical user interfaces generation for easy dataset editing and display. It also provides helpers and application development tools for Python-Qt.

* [guiqwt](https://github.com/PlotPyStack/guiqwt): Efficient 2D data-plotting features (curve/image visualization and related tools) for interactive computing and signal/image processing application development using PythonQwt. Note: ``guiqwt`` has been replaced in 2023 by ``plotpy``.

* [plotpy](https://github.com/PlotPyStack/plotpy): Based on PythonQwt and on the scientific modules NumPy and SciPy, ``plotpy`` is a Python library providing efficient 2D data-plotting features (curve/image visualization and related tools) for interactive computing and signal/image processing application development.

## Some projects using PlotPyStack

The following projects are powered by PlotPyStack:

* [DataLab](https://codra-ingenierie-informatique.github.io/DataLab/): Open-source software for scientific data analysis and visualization

* [ModuleTester](https://github.com/Codra-Ingenierie-Informatique/ModuleTester): Library providing a GUI to manage and run tests on a Python module

* [PyPlanning](https://github.com/Codra-Ingenierie-Informatique/PyPlanning): Small planning tool to manage team schedules and to quickly create simple project plannings

* ...and many other projects which are not open-source, unfortunately.
