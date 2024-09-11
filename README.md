# SICApi
User APIs of Standard Integrated Cell Assembly

In Development.   
**SICA** is a operating system to automate Biolab equipments.   
**SICApi** defines the standard format of user APIs to control the operating system.

## Our principles
#### 1. Only Python enough for wet-lab researchers.   
Python is a familiar language to Biology researchers. However, in order to introduce automation into the laboratory, learning C is essential to access embedded systems. Since they are too busy to do this, SICApi is designed to control a operating system with just python. In addition to conducting experiments, it is also designed that a framework of new equipment can be easily integrated into the system through built-in APIs.

#### 2. Operation on matrix 
Each object in experiment can be expressed as a value or a submatrix of multi-dimensional matrix. For example, 96 well plate is expressed to a 2D matrix with 8 rows and 12 columns. Here, depending on experiment process, extra dimensions may be expanded to the matrix. This matrix abstraction is intuitive to illustrate experimental variables subjecting to objects throughout experiment progress. In addition, this matrix structure enables to construct direct pipeline with Machine Learning API packages. This will help to alleviate bottleneck problem in a process between AI-driven canditate molecule selection and actual validation.

#### 3. Keep it Pythonic
Operating system of SICA is programmed with C++ and Python package SICApi wraps it. By reducing interference of static values, SICApi can be coded with no difference as Python encourages.
