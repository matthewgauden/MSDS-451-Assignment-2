# MSDS-451-Assignment-2

## Overview
This assignment aimed to solve a portfolio optimization problem using Monte Carlo methods. Portfolio optimization involved four risky assets of my choosing. The four assets chosen are: Coca-Cola (KO), Apple (AAPL), Amazon (AMZN), and Netflix (NFLX). Each asset has expected annual returns, associated volatilities (standard deviations), and both correlation and covariance matrices. The portfolio optimization problem involves solving for the portfolio weights given the investment constraints. The optimization problem was solved using Monte Carlo methods rather than those of standard linear programming techniques. There were two constraints given for the assignment: 1) A conservative asset allocation strategy that only employs long positions and 2) a more flexible strategy that enables the investor to use both short and long positions in their portfolio. 

## Guide
The following project can be completed in a Jupyter Notebook environment or the Python script environment. For the purposes of this assignment it was completed using Jupyter Notebook. You can find both the ipnyb file and the associated HTML in this Assignment 2 repository. There is also my technical report that serves as the write-up to the code, and the results of the experiments. 

## Build Steps and AI Disclaimer
The jumpstart code given with this assignment was not in Python, but in R. Occasional use of Gemini in Google Colab was implemented in order to translate some complicated sections of R code into a Python format. Most of the Monte Carlo methods I was familiar with already from previous courses, but translating the ggplot to one that can be performed by seaborn was tricky and Gemini helped with the formatting details such as Facetgrid to show the side-by-side comparison of investment strategies. 
