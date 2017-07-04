  <script type="text/javascript" async
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-MML-AM_CHTML">
</script>
<div class="fluid-row" id="header">

# UNASSISTED QUANTITATIVE EVALUATION OF DESPECKLING FILTERS

#### Luis Gomez$^{1}$, Raydonal Ospina$^{2}$ and Alejandro C. Frery$^{3}$

</div>

$^{1}$Department of Electronic Engineering and Automation, University of Las Palmas de G.C., Spain; [luis.gomez@ulpgc.es](mailto:luis.gomez@ulpgc.es)

$^{2}$Departamento de Estatística. Universidade Federal de Pernambuco, Brazil; [rayospina@gmail.com](mailto:rayospina@gmail.com)

$^{3}$  LaCCAN – Laboratório de Computação Científica e Análise Numérica. Universidade Federal de Alagoas, Brazil; [acfrery@laccan.ufal.br](mailto:acfrery@laccan.ufal.br)

<div id="abstract" class="section level3">

### Abstract

SAR (Synthetic Aperture Radar) imaging plays a central role in Remote Sensing due to, among other important features, its ability to provide high-resolution, day-and-night and almost weather-independent images.
SAR images are affected from a granular contamination, speckle, that can be described by a multiplicative model. 
Many despeckling techniques have been proposed in the literature, as well as measures of the quality of the results they provide. 
Assuming the multiplicative model, the observed image $Z$ is the product of two independent fields: the backscatter $X$ and the speckle $Y$. 
The result of any speckle filter is $\widehat X$, an estimator of the backscatter $X$, based solely on the observed data $Z$. 
An ideal estimator would be the one for which the ratio of the observed image to the filtered one $I=Z/\widehat X$ is only speckle: a collection of independent identically distributed samples from Gamma variates. 
We, then, assess the quality of a filter by the closeness of $I$ to the hypothesis that it is adherent to the statistical properties of pure speckle. 
We analyze filters through the ratio image they produce with regards to first- and second-order statistics: the former check marginal properties, while the latter verifies lack of structure. 
A new quantitative image-quality index is then defined, and applied to state-of-the-art despeckling filters. 
This new measure provides consistent results with commonly used quality measures (equivalent number of looks, PSNR, MSSIM, $\beta$ edge correlation, and preservation of the mean), and ranks the filters results also in agreement with their visual analysis.
We conclude our study showing that the proposed measure can be successfully used to optimize the (often many) parameters that define a speckle filter.
</div>

<div id="information" class="section level3">

### Information

*   Subbmitted to [http://www.mdpi.com/journal/remotesensing/special_issues/rsimages](http://www.mdpi.com/journal/remotesensing/special_issues/rsimages).
*   Remote Sensing
*   Title: Unassisted Quantitative Evaluation Of Despeckling Filters.
*   Download: [pdf](https://github.com/Raydonal/UNASSISTED/blob/master/Docs/LGomezROspinaACFrery_SubmittedRemoteSensing.pdf)

</div>

<div id="source-code" class="section level3">

### Source Code

The source codes are accessible at [Here](https://github.com/Raydonal/UNASSISTED/blob/master/Detect_Structure_Matlab.7z). Please read the instructions for installation [Readme](https://github.com/Raydonal/UNASSISTED/blob/master/Installation_Use_Test_README.txt).

* * *

This is an R Markdown document produced by [Raydonal Ospina](mailto:raydonal@de.ufpe.br). Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see [http://rmarkdown.rstudio.com](http://rmarkdown.rstudio.com).

</div>

</div>

