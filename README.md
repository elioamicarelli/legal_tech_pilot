# About this repo

In 2016 I have been in contact with a dutch legal tech start-up named newCobra connected with the ARAG legal insurance group. The start-up had a general interest in exploring options to innovate the current procedures adopted by the ARAG group so they provided to me a heterogeneous sample of the data available in their database. 

Despite the data came from different sources and despite the fact that I do not speak/read/write dutch at all, I identified an interesting subset of observations and build a pilot study around it. Using clients' questions submitted via a web legal platform, I have carried out a pilot study to evaluate the feasibility of automating the classification of legal questions submitted by ARAG's clients via the jurofoon.nl website. 

The reporting task this time was also quite interesting: I had to explain to a non technical audience (the start-up people) how to go along in explaining technical matters (the automation of classification) to their non technical audience (the administrators financing the start-up). The result is the report named "pilot_report.pdf" contained in this repository.

This pilot idea was a success and ARAG decided to assign the implementation to a dutch company called bright cape.

In this repository you will find the following items:

- pilot_report.pdf. The report of this project in pdf format

- pilot_report.Rmd. The report in R markdown allowing to replicate the analysis.

- data_clean.csv, xgbmodel.rda, xgbtrain.rda. Data needed to replicate the analysis using pilot_report.Rmd.

- README.md. This file.
