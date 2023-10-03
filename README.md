# Time-Series Analysis
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/laurentpauwels/timeseriesanalysis.git/HEAD)

Repository for Jupyter Notebook teaching materials. Click the `launch binder` button above to start `binder`, the interactive computational environments for this GitHub repository. The materials are programmed with the statistical computing language `R`.

## Content


1. `intro2TS.ipynb`: Explore, plots, and smooth time-series data.
2. `exploreTS.ipynb`: Moving and weighted averages, exponential smoothing, seasonal data, LOESS.
3. `armaModels.ibynb`: AR, MA, and ARMA models.
4. `selection.ipynb`: ACF, PACF, ADF.
5. `estimateTS.ipynb`: Exploring method of moments, OLS, and Maximum likelihood to estimate time-series data. 
6. `diagnosticTests.ipynb`: Normality tests, Ljung-Box test, overfitting models. 
7. `forecastingTS.ipynb`: Forecasting time-series data, linear trend, ARIMA models, Prediction intervals.  
8. `spectralAnalysis.ipynb`: Spectral density and ARMA models, industrial production, spectrum, periodogram. This Jupyter notebook uses `./data/indprod.csv`.
9. `structuralBreaks.ipynb`: CUSUM, MOSUM, Chow Test, known/unknown break points, multiple break points, and Andrews and Zivot tests.


- `intro2R.ipynb`: is a basic introduction to R with some time-series data as well as basics of programming in R such as creating variables, basic operations, matrix algebra, functions, and loops. It uses the `./data/tut1.csv` dataset.
- `./data`: folder that contains the relevant data.
- `install.R`: contains all the required R packages that need to be installed. This installed when opening a `binder` interactive environment. It can be used to install all the required packages locally.
- `runtime.txt`: r-4.1-2022-01-10, the version of R `binder` installs. 

## References

Robert H. Shumway and David S. Stoffer. _Time Series Analysis and Its Applications: With R Examples_. Springer Texts in Statistics. Springer Cham, 4th Edition, 2017

James D. Hamilton. _Time Series Analysis_. Princeton University Press, 1994.