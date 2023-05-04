# Saturn's Atmosphere in Northern Summer Revealed by JWST/MIRI

Supplementary material for Fletcher et al. (2023)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7891589.svg)](https://doi.org/10.5281/zenodo.7891589)


## Contents

### Flat fields
The `flat fields` directory contains the derived flat fields calculated from the observed Saturn data using the [`construct_flat_field`](https://github.com/JWSTGiantPlanets/pipelines/blob/main/construct_flat_field.py) script in the [pipelines repository](https://github.com/JWSTGiantPlanets/pipelines).

### Quick look visualisations
The `quick_looks` directory contains quick look plots and animations used to visualise each observed data cube. The plots were created by the [`jwst_summary_plots`](https://github.com/JWSTGiantPlanets/pipelines/blob/main/jwst_summary_plots.py) script, and the animations were created by the [`jwst_summary_animation`](https://github.com/JWSTGiantPlanets/pipelines/blob/main/jwst_summary_animation.py) script in the [pipelines repository](https://github.com/JWSTGiantPlanets/pipelines). The visualisations show the data after it has passed through the full reduction pipeline (including desaturation, flat field correction and despiking). The 'difference' animations show the deviation from the zonal average at each wavelength, so can be used to more easily identify discrete features.

### Zonal averages
The `zonal_average_spectra` directory contains the calculated zonal average spectra of Saturn for each channel at planetographic latitudes from 20°S to 90°N. The zonal averages were calculated using the [`zonal_average`](https://github.com/JWSTGiantPlanets/pipelines/blob/main/zonal_average.py) script in the [pipelines repository](https://github.com/JWSTGiantPlanets/pipelines).

The `zonal_average_plots` directory contains plots showing the variation in the zonal average spectra with latitude. Each plot shows the difference between the zonal average spectrum at each latitude and the mean spectrum (averaged over all latitudes) where red areas are brighter than the mean and blue areas are darker.


## See also
The [pipelines repository](https://github.com/JWSTGiantPlanets/pipelines) contains the reduction pipeline code used to reduce and process the data used in this study.
