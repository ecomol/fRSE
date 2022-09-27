# fRSE
fRSE is an R package for estimating the total number of all rare species in under-sampled sites. The methods we used include a highly accurate Bayesian-weighted estimator and two unweighted estimators.


------------------------------------------------------------------------------------------------
Update: 2022-09-27

Our paper has been published in Applied Vegetation Science, please cite it if used.

Update: 2019-06-05


Now version 1.3 is released! This new version fixes a critical bug on the Bayesian-weighted estimators.


------------------------------------------------------------------------------------------------


Note that the difference between fRSE and RSE packages is that RSE package estimates the number of newly found rare species in the additional sample. That is, the estimated rare species have not been recorded or observed in the original sample. By contrast, the fRSE package is to predict the number of total rare species in the additional sample. This means, the estimated value is the sum of newly found rare species and those species that have been previously observed in the original sample but will become rare in the additional sample.  For the latter species, they can be either rare or common the original sample.


The following two cartoons tell the difference between two packages in estimating rare species:


![Image of RSE](https://github.com/ecomol/fRSE/blob/master/RSE.JPG)


![Image of fRSE](https://github.com/ecomol/fRSE/blob/master/fRSE.JPG)



------------------------------------------------------------------------------------------------
For citing the package, please cite the following reference:


Wu Y., Chen Y., Li F.-Q.,Shen T.-J., Nielsen S.E. (2022) Abundance- and incidence-based estimation of total number of rare species in under-sampled sites. Applied Vegetation Sciences, 25, e12649.


------------------------------------------------------------------------------------------------


If users have questions about the usage of the fRSE package, please contact:

Prof. Youhua Chen, email: haydi@126.com; Address: CAS Key Laboratory of Mountain Ecological Restoration and Bioresource Utilization & Ecological Restoration and Biodiversity Conservation Key Laboratory of Sichuan Province, Chengdu Institute of Biology, Chinese Academy of Sciences, Chengdu, 610041.

Prof. Tsung-Jen Shen, email: tjshen@nchu.edu.tw; Address: Institute of Statistics & Department of Applied Mathematics, National Chung Hsing University, 250 Kuo Kuang Road, Taichung, 40227.
