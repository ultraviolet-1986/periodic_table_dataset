# Periodic Table Dataset

A periodic table dataset containing basic element property information.

## Introduction

This data is presented as a CSV file, which contains a header. These data
contain a basic periodic table of elements with a focus on electronegativity,
but also contains data regarding mass.

### Notes on mass data

The 'Mass' column of data contained within this file does not contain
information on element half-life. This is to ensure that all data are presented
in the most basic way possible. This dataset is intended for a very basic
educational use-case.

### Notes on missing data

Some columns within this file are not populated where data are not available.
These elements have been intentionally left blank to ensure all cells contain a
single data-type (such as float, int, string, etc.).

## Load data

The two most common languages used for data science at time of writing are
Python and R. With this in mind, the following code will help to load these data
into your program (providing the correct working directory context is set).

### Python

```python3
import pandas as pd
data = pd.read_csv('periodic_table.csv', header = 1)
```

### R

```R
data <- read.csv(file = 'periodic_table.csv', header = TRUE)
```

## References

- [Periodic Table](https://tinyurl.com/y3pdt4as)
- [Periodic Table: Electronegativity](https://tinyurl.com/y32wrxxg)
