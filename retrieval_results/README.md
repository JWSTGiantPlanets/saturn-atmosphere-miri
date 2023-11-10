# Repository for Retrieval Results
Fletcher et al. (2023), Saturn’s Atmosphere in Northern Summer Revealed by JWST/MIRI, JGR: Planets, Volume 128, e2023JE007924

## Temperature Profiles
Saturn's atmospheric temperatures are displayed in Fig. 14, along with the derived vertical zonal windshear and the thermal winds.  Pressures (in atm) are provided in `sat_press.csv`, latitudes (planetographic) are in `sat_lat.csv`, the retrieved temperatures on this pressure/latitude grid are in `sat_temp.csv`, with associated uncertainties in `sat_temperr.csv`.  Note that these temperatures are only valid in the troposphere and stratosphere in the ranges described in the main paper.  Temperatures provided at lower/higher pressures are from simple extrapolation back to our prior, and are not determined from the JWST data.

## Tropospheric Composition
Cross-sections of Saturn's phosphine, ammonia, and water derived from the 4.9-7.3 µm spectrum are shown in Figure 15.  For the three gases, we provide three CSV files:  one containing the volume mixing ratio (or mole fraction) in ppm/ppb; one containing the relevant latitude grid (planetographic), and one containing the relevant pressure grid (atm).

## Tropospheric Aerosols
Fig. 15 also showed the distribution of Saturn's tropospheric aerosols using the two-cloud system as described in the paper.  The resulting opacities are highly sensitive to the choices of optical properties of the clouds (e.g., size distributions, refractive indices, etc.), but the cross-sections of the optical depth per kilometer, and per bar, are provided (referenced to 5 µm) as the `aer_*.csv` files, alongside their matching pressure (atm) and latitude (planetographic) grids.

## Stratospheric Composition
Figures 16 and 17 of the article show the latitudinal distributions of stratospheric species derived from the 7.3-16.3 µm region of the MIRI spectrum.  Ethane and acetylene were derived as full profiles, and so the results are provided on pressure/latitude grids in the same way as above.  Fig. 17 then provided the 1-mbar latitudinal distributions of multiple species, and these are saved as `species_1mbar_ppX.csv` files, where `ppX` is replaced by ppm, ppb, or ppt as appropriate for the figure.  The latter files contain planetographic latitudes, derived abundances, and uncertainties on those abundances.
