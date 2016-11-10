# FDRhmrf

This package is designed for the false discovery rate (FDR) controlling procedure proposed in [1]. This FDR procedure is based on the two-parameter Ising model (a classical hidden Markov random field) and the local index of significance (LIS; [2,3]), which aims to minimize the false nondiscovery rate (FNR) while controlling FDR at a given level especially for 3D spatial data, e.g., neuroimaging data.

This package is coded in C++, and can be called from Matlab by MEX. Example data are provided, and please see README.pdf for details.

Please cite the article [1] (available at https://deepblue.lib.umich.edu/handle/2027.42/113759) for this package. 

[1] Shu, H., Nan, B., and Koeppe, R. (2015). "Multiple Testing for Neuroimaging via Hidden Markov Random Field". Biometrics, 71, 741-750.

[2] Sun, W., and Cai. T.T. (2009). "Large‐scale multiple testing under dependence". Journal of the Royal Statistical Society, Series B, 71, 393-424.

[3] Wei, Z., Sun, W., Wang, K., and Hakonarson, H. (2009). "Multiple testing in genome-wide association studies via hidden
Markov models". Bioinformatics 25, 2802–2808.





