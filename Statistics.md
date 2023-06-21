# PLS-PM / PLS-SEM

|Authors|Journal|Findings|
|:---|:-----: |--------------------------------------|
[Hair et al. 2022](https://link.springer.com/chapter/10.1007/978-3-030-80519-7_1)|Springer Book|Excellent introductory chapter on PLS-SEM, specifying distinction with CB-SEM, commonly used in popular R packages like lavaan. Introduce the concepts of constructs (LVs), indicators (items/manifest variables), inner and outter models, exogenous vs endogenous LVs (exo = only explaining other LVs)...|
[Csala et al. 2020](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-3286-3)|BMC Bioinformatics|Develop multiset sparse PLS-PM, with code available for R. <br> Particularly useful (over other alternatives such as sparse CCorA, sparse RDA, MOFA...) when want to take into account hierarchical relationships between parts of the dataset... <br> sPLSPM developed here is able to explain higher proportion of variance than MOFA ([Argelaguet et al. 2018](https://doi.org/10.15252/msb.20178124)) <br> sPLSPM is **very** good at rejecting unimportant variables (feature selection through regression penalization is very efficient, in their case they used UST) <br> Suggest using univariate soft thresholding (UST) for penalization (i.e., setting Ridge penalty $\lambda_2$ to infinite) to make it less computationally expensive <br> Latent variables (e.g., the transcriptome) are **linear** combinations of manifest variables (i.e., the genes expressed, forming the transcriptome) <br> Refer to general algorithm for PLS-PM [here](https://doi.org/10.1002/wics.1239).

<br>
<br>

# PLS regression - feature selection

|Authors|Journal|Findings|
|:---|:-----:|--------------------------------------|
[Vohland & Emerling 2011](https://bsssjournals.onlinelibrary.wiley.com/doi/full/10.1111/j.1365-2389.2011.01369.x)|Eur J Soil Sci|PLS regression to SOC and hot-water soil C <br> **Stratified models = better predictions** (first separating soil orders based on physico-chemistry, leading to podzols being treated separately) <br> Genetic algorithms was by far best algorithm for feature selection <br> Not because PLS coefficient further away from 0 that it will necessarily be selected by feature selection algorithm... <br> Larger walelengths were most important to predict soil C (>2000nm especially) <br> achieved quite good predictions for 48 samples, even after stratifying into smaller models per soil type!|


<br> <br>

# General considerations/notions on PLS

## Origin of PLS

## Inclusion of error in dimensionality reduction techniques (contrast between factor analysis vs PCA)

## ........