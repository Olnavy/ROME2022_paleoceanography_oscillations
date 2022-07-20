# ROME2022_paleoceanography_oscillations

# Millennial-scale climate oscillations triggered by deglacial meltwater discharge in last glacial maximum simulations

## Abstract
*Our limited understanding of millennial-scale variability in the context of the last glacial period can be explained by the lack of a reliable modelling framework to study abrupt climate changes under realistic glacial backgrounds. In this article, we describe a new set of long-run Last Glacial Maximum experiments where such climate shifts were triggered by different snapshots of ice-sheet meltwater derived from the early stages of the last deglaciation. Depending on the location and the magnitude of the forcing, we observe three distinct dynamical regimes and highlight a subtle window of opportunity where the climate can sustain oscillations between cold and warm modes. We identify the Eurasian Arctic and Nordic Seas regions as being most sensitive to meltwater discharge in the context of switching to a cold mode, compared to freshwater fluxes from the Laurentide ice sheets. These cold climates follow a consistent pattern in temperature, sea ice and convection, and are largely independent from freshwater release as a result of effective AMOC collapse. Warm modes, on the other hand, show more complexity in their response to the regional pattern of the meltwater input, and within them, we observe significant differences linked to the reorganisation of deep water formation sites and the subpolar gyre. Broadly, the main characteristics of the oscillations, obtained under full-glacial conditions with ice-sheet reconstruction derived meltwater patterns, share similar characteristics with d18O records of the last glacial period, although our experiment design prevents detailed conclusions from being drawn on whether these represent actual Dansgaard-Oeschger events.*

## Reproducibility
Please refer to the Open Research section of the corresponding paper () to access the inputs and outputs to reproduce the data. Before running, you need to indicate that data_folder corresponding to the meltwater input files, LGM inputs, pre-industrial. For each simulations, you should indicate the time_series repositories in your ressources/hadcm3_input copy of pylaeoclim_leeds (Olnavy/pylaeoclim_leeds).

## Experiment names
In the paper, year 0 corresponds to experiment year 1000.

| Experiment name | Experiment labels | Comments |
| ----------- | ----------- | ----------- | 
| XOUPA | CTRL | Initial 1000 years corresponding to spin-up |
| XOUPD/TFGBD | 21.5k | Switched from TFGBD to XOUPD at year 3060 |
| XOUPH | 21k | - |
| TFGBI | 20.7k | - |
| TFGBR/XOUPL | 19.4k | Switched from TFGBR to XOUPL at year 3000 |
| XOUPF | 18.2k | - |
| TFGBJ | 17.8k | - |

## References
The shapefiles were taken from Asis et al. 2017  
The Greenland air temperature proxy were taken from N.G.R.I.P 2004  
The Antarctica air temperature proxy were taken from Barbantet et al. 2006  

Assis, J., Tyberghein, L., Bosch, S., Verbruggen, H., Serrão, E.A. & De Clerck, O. (2017) Bio-ORACLE v2.0: Extending marine data layers for bioclimatic modelling. Global Ecology and Biogeography, 27, 277–284.  
Barbante, C., Barnola, J.-M., Becagli, S., Beer, J., Bigler, M., Boutron, C., . . .EPICA Community Members (2006, November). One-to-one coupling of glacial climate variability in Greenland and Antarctica. Nature, 444 (7116).  
N.G.R.I.P, M. (2004, September). High-resolution record of Northern Hemisphere climate extending into the last interglacial period. Nature, 431 (7005), 147–151.  
