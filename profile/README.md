# PlotPyStack: A Toolkit for Scientific GUI-based Software in Python

## Overview

Welcome to PlotPyStack, a comprehensive toolkit designed to aid in the development of scientific GUI-based software using Python. This organization houses powerful packages, each providing unique functionalities aimed at simplifying data visualization, plotting, and GUI development for scientific applications.

The table below summarizes the packages included in the PlotPyStack organization:

| Package Logo | Package Name  | Short Description                                                |
|--------------|--------------|------------------------------------------------------------------|
| ![PythonQwt Logo](https://raw.githubusercontent.com/PlotPyStack/.github/main/data/PythonQwt.png) | PythonQwt    | Low-level Qt plotting widgets for Python.   |
| ![guidata Logo](https://raw.githubusercontent.com/PlotPyStack/.github/main/data/guidata.png) | guidata      | A Python library for easy dataset manipulation and display.      |
| ![guiqwt Logo](https://raw.githubusercontent.com/PlotPyStack/.github/main/data/guiqwt.png) | guiqwt       | An efficient 2D data-plotting library based on PythonQwt (guiqwt will soon be replaced by plotpy). |
| ![plotpy Logo](https://raw.githubusercontent.com/PlotPyStack/.github/main/data/plotpy.png) | plotpy       | A high-level interface for creating a variety of plot types.     |

For more details about each package, please refer to their respective repositories.

## Details

PlotPyStack is a Python-Qt visualization and scientific GUI stack based on PythonQwt, guidata and plotpy.

PlotPyStack is composed of the following packages:

* [PythonQwt](https://pypi.python.org/pypi/PythonQwt): Python implementation of the Qwt C++ library. The `PythonQwt` project was initiated to solve -at least temporarily- the obsolescence issue of `PyQwt` (the Python-Qwt C++ bindings library) which is no longer maintained. The idea was to translate the original Qwt C++ code to Python and then to optimize some parts of the code by writing new modules based on NumPy and other libraries.

* [guidata](https://pypi.python.org/pypi/guidata): Automatic graphical user interfaces generation for easy dataset editing and display. It also provides helpers and application development tools for Python-Qt.

* [guiqwt](https://pypi.python.org/pypi/guiqwt): Efficient 2D data-plotting features (curve/image visualization and related tools) for interactive computing and signal/image processing application development using PythonQwt. Note: ``guiqwt`` will soon be replaced by ``plotpy``.

* [plotpy](https://pypi.python.org/pypi/plotpy): Based on PythonQwt and on the scientific modules NumPy and SciPy, ``plotpy`` is a Python library providing efficient 2D data-plotting features (curve/image visualization and related tools) for interactive computing and signal/image processing application development.
