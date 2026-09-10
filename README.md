NumPy Analyzer

Project Overview

NumPy Analyzer is a menu-driven Python project built using NumPy and
object-oriented programming. It allows users to create and manipulate
NumPy arrays and perform common numerical operations through an
interactive console menu.

Objective

The objective of this project is to demonstrate practical use of NumPy
arrays, array manipulation, mathematical operations, searching, sorting,
filtering, and statistical calculations in Python.

Technology Used

Python 3

NumPy

Jupyter Notebook

Object-Oriented Programming (OOP)

Features

The program provides the following main options:

Create a NumPy Array

Perform Indexing and Slicing

Perform Mathematical Operations

Combine or Split Arrays

Search, Sort, or Filter Arrays

Compute Aggregates and Statistics

Exit

Array Creation

The analyzer supports:

1D arrays

2D arrays

3D arrays

Users can enter the required dimensions and numeric elements
interactively.

Indexing and Slicing

The project supports:

Accessing individual elements using indexing

Extracting portions of arrays using slicing

Indexing and slicing for 1D, 2D, and 3D arrays

Mathematical Operations

The analyzer supports:

Addition

Subtraction

Multiplication

Division

Dot product

Matrix multiplication

The program also checks for invalid input and division by zero.

Combine and Split Arrays

Users can:

Combine compatible 2D arrays using vertical stacking

Split 2D arrays into multiple sections

Search, Sort, and Filter

The project provides:

Searching for a value and displaying its positions

Sorting arrays

Filtering values using conditions such as >30, <50, ==20, and
other comparison operators

Aggregates and Statistics

The analyzer can calculate:

Sum

Mean

Median

Standard deviation

Variance

Minimum

Maximum

Percentiles

Correlation coefficient

Error Handling

The program includes input validation and handles common invalid inputs
such as:

Non-numeric values

Invalid array dimensions

Invalid indexes

Invalid slicing ranges

Division by zero

Invalid matrix dimensions

Invalid percentile values

Project Structure

NumPy-Analyzer/
│
├── Analyzer.ipynb
└── README.md

How to Run

Install Python 3.

Install NumPy if it is not already installed:

pip install numpy

Open Analyzer.ipynb in Jupyter Notebook or JupyterLab.

Run the main code cell.

Follow the menu displayed in the notebook and enter your choices.

Example Menu

==========================================
           NUMPY ANALYZER
==========================================

Choose an option:
1. Create a Numpy Array
2. Indexing and Slicing
3. Perform Mathematical Operations
4. Combine or Split Arrays
5. Search, Sort, or Filter Arrays
6. Compute Aggregates and Statistics
7. Exit

Implementation

The project uses a DataAnalytics class to organize the analyzer
functionality. It includes separate methods for array creation,
indexing, slicing, mathematical operations, combining and splitting
arrays, searching, sorting, filtering, and statistical calculations.

Conclusion

NumPy Analyzer is a practical demonstration of NumPy and object-oriented
programming in Python. It provides an interactive way to perform a wide
range of array operations and statistical calculations while also
demonstrating input validation and error handling.
