# Sb119-Auger-cascade-microdosimetry

This repository consists of parameter control files designed for the Monte Carlo simulation code called the TOol for PArticle Simulations (TOPAS) developed by Perl et al. (2012). They are intended for use in performing microdosimetry simulations with Auger electron-emitting radionuclides, including <sup>103m</sup>Rh, <sup>103</sup>Pd, <sup>111</sup>In, <sup>119</sup>Sb, <sup>123</sup>I, <sup>125</sup>I, <sup>165</sup>Er, and <sup>Hg</sup>197. The parameter control files make use of the microdosimetry extension (Zhu et al. 2019) and the nBio extension (Schuemann et al. 2019). The files are compatible with TOPAS version 3.9 or better by Perl et al. (2012) which is open source and available at https://www.topasmc.org/. 

These files support the data contained in a manuscript by Zwaniga et al. (2026) that was submitted to _Physics in Medicine and Biology_ in March 2026 and is currently under review.

Overall, the repository contains parameter control files for simulating eight radionuclides with three Auger electron spectra at four positions relative to a DNA volume. 

## Microdosimetry

Lineal energy spectra are scored and the relative biological effectiveness (RBE) is calculated in a cylindrical 2 nm x 2nm DNA model using the microdosimetric kinetic (MK) model using the microdosimetric extension by Zhu et al. (2019). 

## DNA Damage

DNA single-strand breaks (SSBs) and double-strand breaks (DSBs) are scored in a Charlton DNA model with 17.5 eV threshold to induce single-strand breaks and 10 bp separation between two SSBs to form a DSB. 

## Radiolysis

The yield of free radicals is scored as G-values (molecules produced per 100 eV deposited energy) in a DNA volume. 

## References

Zhu, H. et al. The microdosimetric extension in TOPAS: development and comparison with published data. Phys. Med. Biol. 64, 145004 (2019).

Schuemann, J. et al. TOPAS-nBio: An Extension to the TOPAS Simulation Toolkit for Cellular and Sub-cellular Radiobiology. Radiat Res 191, 125–138 (2019).

Zwaniga, A. V., Da Silva, E., and Grafe, J. Microdosimetry, DNA strand breaks, and radiolysis of the <sup>119</sup>Sb Auger electron cascade in targeted radionuclide therapy: a comparative Monte Carlo study. (2026). 
