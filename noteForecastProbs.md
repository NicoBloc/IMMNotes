# Input

* Magnitude of technical variation
* Observed diameters, either as
    * vector of observed diameters, or
    * histogram of observed diameters
* CBPs

# Model fitting

1. Determine w_1
2. Determine mixture model for x > 6 mm
3. Paste together

# Computations

* Observed density and cdf
* True density and cdf
* Various conditional probabilities
* Probability of very major, major, and minor errors as a function of the true and the observed diameter
* Forecast probability
* ZMU
* Probabilities of very major, major, and minor errors

# Print

* CBPs
* Magnitude of technical variation
* n
* Parameters of components
* Probabilities of very major, major, and minor errors
* ZMU

# Plots

* Individual plots
* Q-Q plots
* Masterplots
* Idea: Provide a single function: myPlot(obj, c("hist", "Q-Q", "FP"))
