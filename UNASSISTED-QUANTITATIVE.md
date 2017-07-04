---
output:
  html_document: default
  pdf_document: default
---
<!--
# Author: Raydonal Ospina
# Date : 24/02/2017
# Contact: raydonal@de.ufpe.br
# Version 1.0
# Licence GPL v3
 --> 


---
title: UNASSISTED QUANTITATIVE EVALUATION OF DESPECKLING FILTERS

author: "Luis Gomez $^{1}$, Raydonal Ospina $^{2}$ and Alejandro C. Frery $^{3}$"
#date: "24/02/2017"
output: html_document




---


$^{1}$ \quad Department of Electronic Engineering and Automation, University of Las Palmas de G.C., Spain; luis.gomez@ulpgc.es

$^{2}$  \quad Departamento de Estatística.  Universidade Federal de Pernambuco, Brazil; rayospina@gmail.com 

$^{3}$  \quad LaCCAN -- Laboratório de Computação Científica e Análise Numérica. Universidade Federal de Alagoas, Brazil; acfrery@laccan.ufal.br

### Abstract
SAR (Synthetic Aperture Radar) imaging plays a central role in Remote Sensing due to, among other important features, its ability to provide high-resolution, day-and-night and almost weather-independent images.
SAR images are affected from a granular contamination, speckle, that can be described by a multiplicative model. 
Many despeckling techniques have been proposed in the literature, as well as measures of the quality of the results they provide. 
Assuming the multiplicative model, the observed image $Z$ is the product of two independent fields: the backscatter $X$ and the speckle $Y$. 
The result of any speckle filters is $\widehat X$, an estimator of the backscatter $X$, based solely on the observed data $Z$. 
An ideal estimator would be the one for which the ratio of the observed image to the filtered one $I=Z/\widehat X$ is only speckle: a collection of independent identically distributed samples from Gamma variates. 
We, then, assess the quality of a filter by the closeness of $I$ to the hypothesis that it is adherent to the statistical properties of pure speckle. 
We analyze filters through the ratio image they produce with regards to first- and second-order statistics: the former check marginal properties, while the latter verifies lack of structure. 
A new quantitative image-quality index is then defined, and applied to state-of-the art despeckling filters. 
This new measure provides consistent results with commonly used quality measures (equivalent number of looks, PSNR, MSSIM, $\beta$ edge correlation, and preservation of the mean), and ranks the filters results also in agreement with their visual analysis.


### Information

*   Subbmitted to [http://www.mdpi.com/journal/remotesensing/special_issues/rsimages](http://www.mdpi.com/journal/remotesensing/special_issues/rsimages).
*   Remote Sensing
*   Title: Unassisted Quantitative Evaluation Of Despeckling Filters.
*   Download: [pdf](https://github.com/Raydonal/UNASSISTED/blob/master/Docs/LGomezROspinaACFrery_SubmittedRemoteSensing.pdf)



<!-- ## Reproducible information on paper -->

### Source Code
The source codes are accessible at [Here](http://www.de.ufpe.br/~raydonal/ReproducibleResearch/UNASSISTED/Detect_Structure_Matlab.7z). Please read the instructions for installation [Readme](http://www.de.ufpe.br/~raydonal/ReproducibleResearch/UNASSISTED/Installation_Use_Test_README.txt).



***
This is an R Markdown document produced by <a href="mailto:raydonal@de.ufpe.br">Raydonal Ospina</a>. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.
