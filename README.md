[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Python 3.11](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/downloads/release/python-31110/)
[![DOI](https://zenodo.org/badge/885428157.svg)](https://doi.org/10.5281/zenodo.14188323)




# Modulation of the Northern polar vortex by the Hunga Tonga-Hunga Ha'apai eruption and associated surface response 

**[A. Kuchar](https://github.com/kuchaale/), Timofei Sukhodolov, Gabriel Chiodo, Andrin Jörimann, Jessica Kult-Herdin,
Eugene Rozanov, and Harald Rieder**

Submitted to [Atmospheric Chemistry and Physics](https://egusphere.copernicus.org/preprints/2024/egusphere-2024-1909/).

Code used to process and visualise the model and other data outputs in order to reproduce figures in the manuscript.
Model data are available upon request. All datasets already preprocessed can be found [here](?).

Notebooks for each individual figure as well as for two data tables are in the [`code/` directory](code), while the figures themselves are in the [`plots/` directory](plots).

### Figures
|  #  | Figure                                                                                                                                                                                                    | Notebook                                                                              | Dependencies                                                                                                                                                             |
|:---:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  1 | [Monthly and zonal-mean structure of WV, O3, OH and temperature](plots/?.pdf)                                                                              | [HT_paper_fig1+3.ipynb](code/HT_paper_fig1+3.ipynb)                       |                                                                                                                         |
|  2 | [Weighted zonally-averaged temperature average over low and high latitude and NAM](plots/NAM_lagA_composite_HIonly_FDR.pdf)                                                      | [HT_paper_fig1.ipynb](code/HT_paper_fig2.ipynb)                 |                                                                                                                           |
|  3 | [Sea level pressure abd surface air temperature monthly anomaly in April 2023](plots/?.pdf)                | [HT_paper_fig1+3.ipynb](code/HT_paper_fig1+3.ipynb)|          

### Figures in Appendix
|  #  | Figure                                                                                                                                                                                                    | Notebook                                                                              | Dependencies                                                                                                                                                             |
|:---:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  A1 | [Integrated stratospheric water vapor](plots/?.pdf)                                                                              | [M2SCREAM_SOCOL_paper_figs-A1A.ipynb](code/M2SCREAM_SOCOL_paper_figs-A1A.ipynb), [HT_socol_processing-htt-A1B_A2_A5_A6.ipynb](code/HT_socol_processing-htt-A1B_A2_A5_A6.ipynb)                       |                                                                                                                         |
|  A2 | [Seasonal zonal-mean structure of SAD and WV in SOCOLv4](plots/NAM_lagA_composite_HIonly_FDR.pdf)                                                      | [HT_socol_processing-htt-A1B_A2_A5_A6.ipynb](code/HT_socol_processing-htt-A1B_A2_A5_A6.ipynb)                       |                                                                                                                           |
|  A3 | [Seasonal zonal-mean structure of SAD and WV in GloSSAC and SWOOSH](plots/?.pdf)                | [SWOOSH_water_vapour_FigA3.ipynb](code/SWOOSH_water_vapour_FigA3.ipynb)|  
|  A4 | [Monthly global-mean evolution of temperature, WV and ozone](plots/?.pdf)                | [Randel-like_fig_TE-H2O-O3_FigsA4_A8.ipynb](code/Randel-like_fig_TE-H2O-O3_FigsA4_A8.ipynb)|  
|  A5 | [Seasonal zonal-mean structure of HNO3](plots/?.pdf)                | [HT_socol_processing-htt-A1B_A2_A5_A6.ipynb](code/HT_socol_processing-htt-A1B_A2_A5_A6.ipynb)        |  
|  A6 | [Seasonal zonal-mean structure of HOBr](plots/?.pdf)                | [HT_socol_processing-htt-A1B_A2_A5_A6.ipynb](code/HT_socol_processing-htt-A1B_A2_A5_A6.ipynb)        |  
|  A7 | [Daily anomalies of the Eliassen-Palm flux](plots/?.pdf)                | [
HT_paper_EPF-A7.ipynb](code/
HT_paper_EPF-A7.ipynb)|  
|  A8 | [Monthly geopotential height anomalies (maps)](plots/?.pdf)                | [Randel-like_fig_TE-H2O-O3_FigsA4_A8.ipynb](code/Randel-like_fig_TE-H2O-O3_FigsA4_A8.ipynb)|  
|  A9 | [Daily zonal-mean zonal wind at 10 hPa and 60°N](plots/?.pdf)                | [SSWs_2024_FIG-A9.ipynb](code/SSWs_2024_FIG-A9.ipynb)|  



