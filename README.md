[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Python 3.11](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/downloads/release/python-31110/)
[![DOI](https://zenodo.org/badge/885428157.svg)](https://doi.org/10.5281/zenodo.14188323)




# Modulation of the Northern polar vortex by the Hunga Tonga-Hunga Ha'apai eruption and associated surface response 

**[A. Kuchar](https://github.com/kuchaale/), Timofei Sukhodolov, Gabriel Chiodo, Andrin Jörimann, Jessica Kult-Herdin,
Eugene Rozanov, and Harald Rieder**

Published as [Atmospheric Chemistry and Physics Letter]([https://egusphere.copernicus.org/preprints/2024/egusphere-2024-1909/](https://acp.copernicus.org/articles/25/3623/2025/)).

Code used to process and visualise the model and other data outputs in order to reproduce figures in the manuscript.
Model data are available upon request. All datasets already preprocessed can be found [here](https://data.mendeley.com/preview/hb3whw3nfr?a=6614a963-645d-4599-b9b7-189866c1b9a9).

Notebooks for each individual figure as well as for two data tables are in the [`code/` directory](code), while the figures themselves are in the [`plots/` directory](plots).

### Figures
|  #  | Figure                                                                                                                                                                                                    | Notebook                                                                              | Dependencies                                                                                                                                                             |
|:---:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  1 | [Monthly and zonal-mean structure of WV, O3, OH and temperature](plots/time-evolution_2022-2023_diff_mm_zon-htt-new-globally.pdf)                                                                              | [figure1_axisgrid.ipynb](code/figure1_axisgrid.ipynb)                       |                                                                                                                         |
|  2 | [Weighted zonally-averaged temperature average over low and high latitude and NAM](plots/TE+NAM+EHF_time-evolution_2023-JFMA_FIG2_new.pdf)                                                      | [HT_paper_fig1.ipynb](code/HT_paper_fig2.ipynb)                 |                                                                                                                           |
|  3 | Sea level pressure abd surface air temperature monthly anomaly in April 2023 [plot**A**](plots/psl_map_2023-04_FIG4.pdf), [plot**B**](plots/2t_map_2023-04_FIG4.pdf)                | [HT_paper_fig1+3.ipynb](code/HT_paper_fig1+3.ipynb)|          

### Figures in Appendix
|  #  | Figure                                                                                                                                                                                                    | Notebook                                                                              | Dependencies                                                                                                                                                             |
|:---:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  A1 | Integrated stratospheric water vapor [plot**A**](plots/strat_WV_mass_htt-vs-M2SCREAM-vs-nudged_daily_202201-202212_daily.pdf), [plot**B**](plots/strat_WV_mass_htt_decay.pdf)                                                                              | [M2SCREAM_SOCOL_paper_figs-A1A.ipynb](code/M2SCREAM_SOCOL_paper_figs-A1A.ipynb), [HT_socol_processing-htt-A1B_A2_A5_A6.ipynb](code/HT_socol_processing-htt-A1B_A2_A5_A6.ipynb)                       |                                                                                                                         |
|  A2 | [Seasonal zonal-mean structure of SAD and WV in SOCOLv4](plots/SAD+H2O_m_time-evolution-diff_mm_zon-htt-new_globally2.pdf)                                                      | [HT_socol_processing-htt-A1B_A2_A5_A6.ipynb](code/HT_socol_processing-htt-A1B_A2_A5_A6.ipynb)                       |                                                                                                                           |
|  A3 | [Seasonal zonal-mean structure of SAD and WV in GloSSAC and SWOOSH](plots/combinedanomh2oq+SAD_time-evolution-SWOOSHv02.7+GloSSAC_globally.pdf)                | [SWOOSH_water_vapour_FigA3.ipynb](code/SWOOSH_water_vapour_FigA3.ipynb)|  
|  A4 | [Monthly global-mean evolution of temperature, WV and ozone](plots/TE+H2O+O3_time-evolution_globally.pdf)                | [Randel-like_fig_TE-H2O-O3_FigsA4_A8.ipynb](code/Randel-like_fig_TE-H2O-O3_FigsA4_A8.ipynb)|  
|  A5 | [Seasonal zonal-mean structure of HNO3](plots/HNO3_m_time-evolution-diff_mm_zon-htt-new-globally.pdf)                | [HT_socol_processing-htt-A1B_A2_A5_A6.ipynb](code/HT_socol_processing-htt-A1B_A2_A5_A6.ipynb)        |  
|  A6 | [Seasonal zonal-mean structure of HOBr](plots/HOBr_m_time-evolution-diff_mm_zon-htt-new-globally.pdf)                | [HT_socol_processing-htt-A1B_A2_A5_A6.ipynb](code/HT_socol_processing-htt-A1B_A2_A5_A6.ipynb)        |  
|  A7 | [Daily anomalies of the Eliassen-Palm flux](plots/EPFD_plot_2023-March-1-30-nup-crop.pdf)                | [HT_paper_EPF-A7.ipynb](code/HT_paper_EPF-A7.ipynb) |  
|  A8 | [Monthly geopotential height anomalies (maps)](plots/zg_map_2023-04_alaSLP_multi-plevs.pdf)                | [Randel-like_fig_TE-H2O-O3_FigsA4_A8.ipynb](code/Randel-like_fig_TE-H2O-O3_FigsA4_A8.ipynb)|  
|  A9 | [Daily zonal-mean zonal wind at 10 hPa and 60°N](plots/ZMZW60N10hPa_SSWs.pdf)                | [SSWs_2024_FIG-A9.ipynb](code/SSWs_2024_FIG-A9.ipynb)|  



