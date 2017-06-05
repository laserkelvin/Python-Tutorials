# Python Tutorial

This set of tutorials are written to introduce someone in science to computing and data analysis using Python - a language commonly used in fields ranging from astronomy, data science, and web/phone app development.

As we'll see throughout the tutorials, Python - in the context of scientific computing - is in a unique position among other programming languages: it has the capability to run interactively, and with a wide host of open-source libraries it is like MatLab, only with much more advantages.

Like MatLab, there are tools to perform vector operations, least-squares fitting, plotting, and any other task you may perform during data analysis. Unlike MatLab, Python is easily portable, available for free, and receives support from a much larger user base. Comparing the two langauges, the code repository Github has seen (at the time of writing) a much larger use of Python than Matlab: the former has ~27 times more active repositories than the latter (as a gross simplification, each "repo" is a project/library). Projects like Jupyter have spawned with the express purpose of facilitating data analysis using Python.

The tutorials are all run from Jupyter notebooks. These will serve as notes and a reference for whenever a task/setting is encountered.

## Tutorial 1 - Basic Python

This chapter focuses on providing a foundation to Python: how to run Python, the basic data types, and how to write functions to perform tasks.

### Topics covered:

- Hello world!
    - Executing commands
    - Printing
- Data types
    - Segue from inability to print a combination of number and words
    - Have to wrap as a `str` type
    - `int`, `float`, `str`
    - `list`, `dict`
- Functions
    - How to define `func` in Python
    - Basic hello world function
    - Basic "print a number"
    - Basic arithmetic
- Iterating in Python
    - `for` loops
    - `list` comprehension (contrast with C++)
    - `dict` looping
- External libraries
    - Importing a function
    - Importing installed packages (`os`, `shutil`)

## Tutorial 2 - Numerical Python

This chapter focuses on performing numerical analysis using Python. The idea I'll try to promote is that Python is a very, very powerful tool for the sciences. Starting from basic operations, we'll move towards progressively science-relevant topics, such as basis functions. This will segue into the next chapter, where we will plot the results of these analyses.

### Topics covered:

- Introduction to `numpy`
    - `numpy` data types
        - `array`
    - Vector Operations
        - BEDMAS
        - Matrix/Array multiplication
        - Normalization
        - Diagonalization
    - Comparison of operation times
        - List vs. Array operation
    - Loading text data
- Introduction to `scipy`
    - Import constants
    - Common basis functions
    - Application to harmonic oscillator

## Tutorial 3 - Plotting

This chapter provides a very, very elementary look at plotting using Python interfaces, with more emphasis on `matplotlib`. The goal is to provide the basic tools for plotting, and demonstrate how you can make publication quality plots (if you put the time and effort...)

### Topics covered:

- Matplotlib
    - Basic plotting
    - Publication quality demonstration
    - Saving/exporting figures

- Interactive plotting with Plotly
    - Very basic plotting
    - Interaction

## Tutorial 4 - Parsing/controlling data

This chapter is predominantly a `pandas` tutorial in the guise of data parsing/control. The goal is to provide the basic tools common in (data) science; reading in data with Python, cleaning up the data to make it analyzable, and outputting the result. We'll highlight this with some exemplar data, followed by writing functions ourselves to read in the .cat output of a Pickett file.

### Topics covered:

- Parsing nice data with `pandas`
    - Reading csv files with `pandas`
    - Operations with `pandas`
        - Column control
        - Indexing
    - Plotting with `pandas`
    - Exporting analyses
        - Output to csv
        - Output to LaTeX

- Parsing ugly data with `pandas`
    - Case study with a Pickett output file

## Tutorial 5 - Automating the mundane

This chapter focuses on trying to improve our quality of life with Python. Lots of tasks that we do require repetition (prone to human error) and reproducibility. I'll provide a brief showcase of two tools that I've developed in Python with those two things in mind.

- Introduction to automation with Python
    - File operations with `os` and `shutil`
    - `glob`
    - Examples with _ab initio_ stuff
    - Examples with PICKETT
