# Project name

Simulation_SDMM


# Description


Monte Carlo simulation for the Stratified Decision-Making Model (SDMM)


# How to Use

You can run the code in the R Studio.

Input parameters are YZ, N, M, and B.

N is the number of status or number of utility matrices. Insert the number of status (at least 2).

YZ is the number of cycles in simulation.

M is the number of outcomes. Insert the number of outcomes (at least 2).

B is the number of strategies. Insert the number of strategies (at least 2).

The matrix S (state transition probability matrix) will be generated based on your inputs.

The UTS (Utility Status) matrix will be generated which is in fact representation of all N utility matrices in one matrix.

The after transition pay off matrix (ATPFM) will be generated by crossproducting the S and UTS.

EMV is the expected monetary value vector for all strategies. It has B rows (number of strategies) and 1 column.

The SIM_EMV is the simulation result for the EMVs. It has B rows representing number of strategies and YZ columns representing number of simulations or cycles.

The rowMeans generates the average value of EMVs for each strategy.


# References


# Author info

Check out my personal website: https://vafadarnikjoo.net/

# Cite the code 

# License
MIT License

Copyright (c) 2022 Amin Vafadarnikjoo

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
