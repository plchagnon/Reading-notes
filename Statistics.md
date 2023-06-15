# PLS-PM / PLS-SEM

|Authors|Journal|Findings|
|:---|:-----: |--------------------------------------|
[Hair et al. 2022](https://link.springer.com/chapter/10.1007/978-3-030-80519-7_1)|Springer Book|Excellent introductory chapter on PLS-SEM, specifying distinction with CB-SEM, commonly used in popular R packages like lavaan. Introduce the concepts of constructs (LVs), indicators (items/manifest variables), inner and outter models, exogenous vs endogenous LVs (exo = only explaining other LVs)...|

<br>
<br>

# PLS regression - feature selection

|Authors|Journal|Findings|
|:---|:-----:|--------------------------------------|
[Vohland & Emerling 2011](https://bsssjournals.onlinelibrary.wiley.com/doi/full/10.1111/j.1365-2389.2011.01369.x)|Eur J Soil Sci|PLS regression to SOC and hot-water soil C <br> **Stratified models = better predictions** (first separating soil orders based on physico-chemistry, leading to podzols being treated separately) <br> Genetic algorithms was by far best algorithm for feature selection <br> Not because PLS coefficient further away from 0 that it will necessarily be selected by feature selection algorithm... <br> Larger walelengths were most important to predict soil C (>2000nm especially) <br> achieved quite good predictions for 48 samples, even after stratifying into smaller models per soil type!|


