<style type="text/css">.main-container { max-width: 940px; margin-left: auto; margin-right: auto; } code { color: inherit; background-color: rgba(0, 0, 0, 0.04); } img { max-width:100%; height: auto; } .tabbed-pane { padding-top: 12px; } button.code-folding-btn:focus { outline: none; }</style>

<div class="container-fluid main-container"><script>$(document).ready(function () { window.buildTabsets("TOC"); });</script>

<div class="fluid-row" id="header">

# UNASSISTED QUANTITATIVE EVALUATION OF DESPECKLING FILTERS

#### _Luis Gomez <span class="math inline">\(^{1}\)</span>, Raydonal Ospina <span class="math inline">\(^{2}\)</span> and Alejandro C. Frery <span class="math inline">\(^{3}\)</span>_

</div>

<span class="math inline">\(^{1}\)</span> Department of Electronic Engineering and Automation, University of Las Palmas de G.C., Spain; [luis.gomez@ulpgc.es](mailto:luis.gomez@ulpgc.es)

<span class="math inline">\(^{2}\)</span> Departamento de Estatística. Universidade Federal de Pernambuco, Brazil; [rayospina@gmail.com](mailto:rayospina@gmail.com)

<span class="math inline">\(^{3}\)</span> LaCCAN – Laboratório de Computação Científica e Análise Numérica. Universidade Federal de Alagoas, Brazil; [acfrery@laccan.ufal.br](mailto:acfrery@laccan.ufal.br)

<div id="abstract" class="section level3">

### Abstract

SAR (Synthetic Aperture Radar) imaging plays a central role in Remote Sensing due to, among other important features, its ability to provide high-resolution, day-and-night and almost weather-independent images. SAR images are affected from a granular contamination, speckle, that can be described by a multiplicative model. Many despeckling techniques have been proposed in the literature, as well as measures of the quality of the results they provide. Assuming the multiplicative model, the observed image <span class="math inline">\(Z\)</span> is the product of two independent fields: the backscatter <span class="math inline">\(X\)</span> and the speckle <span class="math inline">\(Y\)</span>. The result of any speckle filters is <span class="math inline">\(\widehat X\)</span>, an estimator of the backscatter <span class="math inline">\(X\)</span>, based solely on the observed data <span class="math inline">\(Z\)</span>. An ideal estimator would be the one for which the ratio of the observed image to the filtered one <span class="math inline">\(I=Z/\widehat X\)</span> is only speckle: a collection of independent identically distributed samples from Gamma variates. We, then, assess the quality of a filter by the closeness of <span class="math inline">\(I\)</span> to the hypothesis that it is adherent to the statistical properties of pure speckle. We analyze filters through the ratio image they produce with regards to first- and second-order statistics: the former check marginal properties, while the latter verifies lack of structure. A new quantitative image-quality index is then defined, and applied to state-of-the art despeckling filters. This new measure provides consistent results with commonly used quality measures (equivalent number of looks, PSNR, MSSIM, <span class="math inline">\(\beta\)</span> edge correlation, and preservation of the mean), and ranks the filters results also in agreement with their visual analysis.

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

<script>// add bootstrap table styles to pandoc tables function bootstrapStylePandocTables() { $('tr.header').parent('thead').parent('table').addClass('table table-condensed'); } $(document).ready(function () { bootstrapStylePandocTables(); });</script> <script>(function () { var script = document.createElement("script"); script.type = "text/javascript"; script.src = "https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"; document.getElementsByTagName("head")[0].appendChild(script); })();</script>