# Eyetracking: Analysis of tracking participants' eye movements as they viewed photos of arachnids and other arthropods 

The following data and code are provided as a reference for the associated publication in prep.

## Directories / Files Explanations

**Directories**

- *figures_tables*: contains all of the figures and tables for publication plus figures exploring left-right photo bias

- *pairedImages&Raw*: slide deck, raw data, and wrangled data for repeated measures tests

**Files**

- *analysis_v...Rmd*: markdown files containing code for analysis; more recent drafts have higher version numbers; in analysis_v4.Rmd, first half of code is for averaging across slides and the second half is all slide observations

- *averages.RDS*: contains code-calculated averages across slides; use this one, not SpiderPairedData.csv

- *repeated_measures.csv*: has all observations and cleaned

- *SpiderPairedData.csv*: contains the hand-calculated averages across slides; use averages.RDS - butterfly is off when hand-calculated

## Current Status

For each dual photo comparison (for example, butterfly vs spider) there were ten unique pairings that every participant observed, including 5 with the spider on the right and 5 on the left. As of July 16th, 2025, we had finished analysis and visualization using the averages across 10 observations (slides in pairedImages&Raw/ELE_Images.pdf) for each comparison. However, there were a couple of things that we checked recently having to do with the assumptions made by averaging across observations. 

1. We tested whether we get the same results when using all possible observations. This test yielded slightly different results, which as summarized in figures_tables/tables_compared.docx where results from the simpler (average) are highlighted in blue and the more complex (all observations) are highlighted in yellow. All other (uncolored) cells in the table represent the simpler model results. 

2. We looked for side bias (are participants always looking to the left first regardless of whether to spider is left or right). These findings are visualized in figures_tables/SlideVariation.docx. First fixation time, first run dwell time, and run count all seem to follow a pattern of a participant "reading" left to right. Total dwell time seems to be less impacted by this bias.




