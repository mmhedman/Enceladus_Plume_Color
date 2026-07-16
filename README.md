This repository contains the code used to perform the data analysis reported in the paper "Spectral features in the visible spectra of the Enceladus particle plume and E ring: Potential evidence of organic materials and/or missing sub-micron particles" by Hedman and MacKenzie. 

The Jupyter program Satmooncolors.ipynb contains the code needed to make Figure 1, which shows the visible color ratios of Saturn's moons measured by ISS. This uses data stored in the IDL save file getallcolors_err_063026.sav

The Jupyter program Enceladus_Surface.ipynb was used to make Figure 2, which shows the visible spectra of Enceladus' surface. This uses VIMS data stored in S12_ENCELADUS_VIMS_cubeconvert, which are variants of the calibrated VIMS cubed.

The Jupyter program MieSpecs_Examples.ipynb contains the code used to make Figure 3, which shows predicted plume spectra. This program uses the PyMieScatt package. 

The Jupyter program imagedisplay_Enceladus142.ipynb contains the code used to make Figure 4 and the Table 2. This code takes five images saved in the directory 142_PLMHPHR001 and makes an image showing the rescaled images, brightness profiles and low-resolution spectra.

The Jupyter program encplume_S16vimsspec_v2.ipynb contains the code used to make Figures 5 and 6, as well as Table 5. This program processes the VIMS spectra of the E ring and plume derived from data files saved in the directory S16_Enc. 
